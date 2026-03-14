# Casos de Teste: Sauce Demo (Swag Labs) 🧪

Este documento contém os cenários de teste manuais para as principais funcionalidades do site.


| ID | Cenário | Passo a Passo | Resultado Esperado | Status |
|:---|:---|:---|:---|:---|
| **CT01** | Login com sucesso | 1. Acessar o site <br> 2. Digitar `standard_user` <br> 3. Digitar `secret_sauce` <br> 4. Clicar em Login | O usuário deve acessar a página de produtos. | ✅ Passou |
| **CT02** | Login com senha incorreta | 1. Acessar o site <br> 2. Digitar `standard_user` <br> 3. Digitar `senha_errada` <br> 4. Clicar em Login | Exibir mensagem: "Username and password do not match". | ⬜ Pendente |
| **CT03** | Adicionar produto ao carrinho | 1. Estar logado <br> 2. Escolher um produto <br> 3. Clicar em "Add to cart" | O botão deve mudar para "Remove" e o ícone do carrinho marcar "1". | ⬜ Pendente |
| **CT04** | Remover produto do carrinho | 1. Ter um item no carrinho <br> 2. Clicar no botão "Remove" | O botão deve voltar para "Add to cart" e o contador do carrinho sumir. | ⬜ Pendente |
| **CT05** | Login com usuário bloqueado | 1. Acessar o site <br> 2. Digitar `locked_out_user` <br> 3. Digitar `secret_sauce` <br> 4. Clicar em Login | Exibir mensagem: "Sorry, this user has been locked out". | ⬜ Pendente |

---
*Legenda: ⬜ Pendente | ✅ Passou | ❌ Falhou*
