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
