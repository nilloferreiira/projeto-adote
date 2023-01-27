
![Logo of the project]('/templates/static/usuarios/img/logo_adote.png') 
<!-- tire print do logo da aplicacao e coloque na pasta-->

## (ADO.TE)

Essa é uma aplicação feita em python e django, com o objetivo de ser uma ferramenta para facilitar na adoção de animais em situação de rua

## Tecnologias 

Aqui estão as tecnologias usadas no projeto

* Python  3.11.0
* Django  4.1.5

## Features

As principais features da aplicação:
 - Cadastro de usuários
 - Autenticação de usuários
 - Cadastro e remação de animais 
 - Listagem dos animais
 - Buscar os pets cadastrados
 - Ver o perfil do pet
 - Solicitar adoção e ver se é valida
 - Dashboard sobre as adoções

## Como executar:

* Dependências
  - Python  
  - django
  
* Para rodar o projeto.
  
  - no windows use `python manage.py run server` no terminal
  - no mac/linux `python3 manage.py run server`
  - va para a url na porta local `/auth/cadastro/`
  - cadastre seu usuário e depois va para a url `/auth/login/`
  - faça login com o usuário e senha cadastrados
  - cadastre um pet na url `divulgar/novo_pet/`
  - você vai ser redirecionado para sua pagina com todos os seus pets cadastrados
  - se quiser pesquisar um pet para adotar va para url `/adotar/`
  - para aceitar ou recusar um pedido de adoção, logado na conta do dono do pet va para url `divulgar/ver_pedido_adocao/`
  - se quiser ver a dashboard va para url `/divulgar/dashboard/`
  - e por ultimo se quiser sair do usuário q está logado e logar em outro basta digitar `/auth/sair/`


## Interface <!-- tire print das pags da aplicação, suba elas dentro do arquivo da aplicação e então pegue o link delas pego github-->

### 1 - Página de cadastro.

![Cadastro](/readme-img/cadastro.PNG)

### 2 - Página de login.

![Login](/readme-img/login.PNG)

### 3 - Cadastrar um pet.

![NovoPet](/readme-img/novo_pet.PNG)

### 4 - Seus pets.

![SeusPets](/readme-img/seus_pets.PNG)

### 5 - Ver pedidos de adoção.

![Solicitação Adoção](/readme-img/ver_pedido_adocao.PNG)

### 6 - Procurar um pet para adotar.

![BuscarPets](/readme-img/listar_pets.PNG)

### 7 - Informações do pet

![VerPet](/readme-img/ver_pet.PNG)

### 8 - Dashboard.

![Dashboard](/readme-img/dashboard.PNG)

## Links
  - Repositório: https://github.com/nilloferreiira/projeto-adote
    - Em caso de bugs, por favor mande um email informando para danillodana@outlook.com

  ## Authors

  * **Danillo Ferreira Araujo** 
  - projeto desenvolvido durante a PystackWeek, foi minha introdução ao python e django
  Se puder me siga no github!
  Obrigado por visitar e bom codigo!