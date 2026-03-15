# Bug Report: Usuário bloqueado consegue realizar login 🐞

**ID:** BUG001  
**Status:** Aberto  
**Severidade:** Crítica (Falha de Segurança)  
**Prioridade:** Alta  

### 1. Descrição
O sistema permite que o usuário com o status "locked_out_user" (bloqueado) realize login e acesse a área de produtos, ignorando a restrição de conta.

### 2. Passos para Reproduzir
1. Acessar o site [Sauce Demo](https://www.saucedemo.com)
2. No campo 'Username', digitar: `locked_out_user`
3. No campo 'Password', digitar: `secret_sauce`
4. Clicar no botão 'Login'

### 3. Resultado Esperado
O sistema deve impedir o acesso e exibir a mensagem: *"Epic sadface: Sorry, this user has been locked out."*

### 4. Resultado Atual
O sistema realiza o login com sucesso e redireciona o usuário para a página `/inventory.html`.

### 5. Evidências
* [Aqui você pode colocar o link para o print que você tirou do login funcionando por engano]

### 6. Ambiente de Teste
- **Navegador:** Google Chrome
- **Sistema Operacional:** Windows 10/11
- **Dispositivo:** Desktop
