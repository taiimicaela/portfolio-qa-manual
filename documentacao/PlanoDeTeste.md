# Plano de Teste: Sauce Demo (Swag Labs) 🧪

## 1. Introdução
Este documento descreve a estratégia de teste para o e-commerce fictício Sauce Demo. O objetivo é garantir que as funcionalidades básicas de login e carrinho funcionem corretamente.

## 2. Escopo (O que será testado)
- **Autenticação:** Login com diferentes tipos de usuários (sucesso, erro e bloqueio).
- **Inventário:** Visualização de produtos e preços.
- **Carrinho:** Adição e remoção de itens.
- **Checkout:** Fluxo básico de finalização de compra.

## 3. Ferramentas
- **Tipo de Teste:** Manual.
- **Gerenciamento:** GitHub (Issues e Projetos).
- **Ambiente:** Navegador Google Chrome / Desktop.
- **Site de Teste:** [https://www.saucedemo.com](https://www.saucedemo.com)

## 4. Critérios de Aceitação
- O usuário deve conseguir logar com credenciais válidas.
- Mensagens de erro devem aparecer para dados inválidos.
- O contador do carrinho deve atualizar em tempo real ao adicionar produtos.

## 5. Riscos
- O site de terceiros pode ficar fora do ar durante os testes.
- Alterações automáticas no site podem invalidar os casos de teste existentes.
