 ![Webbing Brasil](https://webbingbrasil.com.br/images/logo.png)

# Desafio - Desenvolvedor Fullstack Pleno
Este desafio foi projetado para avaliar a sua capacidade técnica como candidato à vaga de Desenvolvedor Fullstack Pleno.

## Instruções
- Faça um fork deste repositório;
- Utilize alguma das tecnologias (front-end e back-end) informadas na proposta desse desafio;
- Crie um passo a passo de como rodar a sua aplicação;
- Após finalizar, submeta um pull request e aguarde nossa avaliação.

## Proposta
Você deverá desenvolver um sistema de Quiz. Para isso, separaremos a proposta desse desafio em duas etapas:

**Back-end:**
Desenvolva uma API utilizando PHP com o framework Lumen que contenha as seguintes rotas:
- `/register` - [POST] - esta rota deve cadastrar um usuário;
- `/login` - [POST] - esta rota deve autenticar um usuário;
- `/quiz` - [GET] - esta rota deve listar os questionarios disponiveis;
- `/quiz/{quiz}` - [GET] - esta rota deve retornar as perguntas de um questionario;
- `/answer/{quiz}` - [POST] - esta rota deve salvar as respostas do questionario;

**Front-end:**
Desenvolva uma aplicação web utilizando NextJS para atender as seguintes histórias:
 - Eu como usuário desejo me cadastrar;
 - Eu como usuário desejo realizar login;
 - Eu como usuário autenticado desejo visualizar os questionarios disponíveis;
 - Eu como usuário autenticado desejo iniciar um questionario;
 - Eu como usuário autenticado desejo responder as perguntas do questionario;
 - Eu como usuário autenticado desejo visualizar ao final do questionario a minha porcentagem de acertos;

> **Observações:**
> - Sua aplicação web DEVE se comunicar com sua API;
> - Você DEVE utilizar um banco de dados para armazenar as informações necessarias.
> - Sua aplicaçaõ web DEVE funcionar usando SSR
