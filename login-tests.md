
# Testes de Login

## ✅ Versão Final (Profissional)

(versões corrigidas)

## CT-002 - Login com senha inválida

ID: CT-002
Título: Login com senha inválida

Pré-condição:
Usuário cadastrado no sistema

Passos:
1. Acessar a página de login
2. Inserir email válido
3. Inserir senha inválida
4. Clicar no botão "Entrar"

Resultado esperado:
O sistema deve exibir uma mensagem de erro informando que a senha é inválida e não permitir o login

## CT-003 - Login com campo vazio

ID: CT-003
Título: Tentativa de login com campo de senha vazio

Pré-condição:
Usuário cadastrado no sistema

Passos:
1. Acessar a página de login
2. Inserir email válido
3. Deixar o campo de senha vazio
4. Clicar no botão "Entrar"

Resultado esperado:
O sistema deve exibir uma mensagem informando que o campo de senha é obrigatório e não permitir o login

## CT-004 - Login com sucesso

ID: CT-004
Título: Login com credenciais válidas

Pré-condição:
Usuário cadastrado no sistema

Passos:
1. Acessar a página de login
2. Inserir email válido
3. Inserir senha válida
4. Clicar no botão "Entrar"

Resultado esperado:
O sistema deve autenticar o usuário com sucesso e redirecioná-lo para a página inicial/dashboard

## CT-005 - Email inválido

ID: CT-005
Título: Login com email inválido

Pré-condição:
Usuário cadastrado no sistema

Passos:
1. Acessar a página de login
2. Inserir um email em formato inválido
3. Inserir uma senha válida
4. Clicar no botão "Entrar"

Resultado esperado:
O sistema deve exibir uma mensagem informando que o email é inválido e não permitir o login

## CT-006 - Campos vazios

ID: CT-006
Título: Tentativa de login com campos de email e senha vazios

Pré-condição:
Usuário não autenticado no sistema

Passos:
1. Acessar a página de login
2. Não inserir email
3. Não inserir senha
4. Clicar no botão "Entrar"

Resultado esperado:
O sistema deve exibir mensagens informando que os campos de email e senha são obrigatórios e não permitir o login


---

## 📚 Versão Inicial (Aprendizado)

(versões antigas)

# Testes de Login

## CT-002 - Login com senha inválida
ID: teste - 02 
titulo: Login com senha invalida 
Passos: acessar o site inserir email valido inserir senha invalida 
resultado: mensagem de "senha invalida"

## CT-003 - Login com campo vazio
ID: CT - 03 
titulo: Login com campo de senha vazio 
pré-condição: usuário cadastro no sistema 
passos: acessar site acessar campo de login inserir email valido deixar campo de senha vazio clicar no botão entrar 
resultado esperado: campo de senha simbolizar a ausência de senha, não permitir o login

## CT-004 - Login com sucesso
ID: CT-004 
Título: Tentativa de Login com Sucesso 
Passos: acessar a pagina de login, inserir email valido, inserir senha valida, clicar no botão entrar 
Resultado esperado: Login com sucesso

## CT-005 - Email inválido
ID: CT-005 
Título: Login com Email Inválido 
Pré-condição: Usuario Cadastro no Sistema 
Passos: acessar a pagina de login inserir email invalido inserir senha valida clicar no botao de "entrar" 
resultado esperado: o sistema deve exibir uma mensagem informando que o campo de email é invalido e nao permitir o login

## CT-006 - Campos vazios
ID: CT-006 
Título: Login com campos vazios Pré-condição: Cadastro de usuário 
Passos: 
1- Acessar pagina de Login 
2- Não inserir email 
3- Não inserir senha 
4- Clicar no botão de "entrar" 
Resultado esperado: o sistema deve informar que campo de email e senha precisam ser preenchidos e não permitir a entrada

Adicionando testes de login
