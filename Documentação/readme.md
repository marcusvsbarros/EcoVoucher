<span id="topo">

<h1 align="center">Sprint 1: 13/05/2024 a 27/05/2024</h1>

<p align="center">
    <a href="#objetivos">Objetivos da sprint</a> &nbsp |&nbsp &nbsp
    <a href="#entregas">Entregas</a> &nbsp |&nbsp &nbsp
    <a href="#metricas">Métricas do time</a> &nbsp |&nbsp &nbsp
    <a href="#links">Links úteis</a>
</p>

O projeto se baseia no desenvolvimento de um site para troca de resíduo reciclável por pontos, esses pontos poderão ser trocados por itens de cesta básica aos usuários, os usuários deverão se cadastrar no site e, ao depositar o resíduo em um equipamento, equipamento esse fora do escopo de desenvolvimento, será apresentado a pontuação. Tendo em mente o MVC, a primeira sprint se deu com a criação de um fluxo básico de criação de usuários, login e páginas de navegação. Para isso, foram levantados e validados os requisitos e o protótipo, construindo os serviços e interfaces visando uma entrega de grande valor condizente com as necessidades dos usuários.

<span id="objetivos">
    
##  Objetivos da Sprint
Os requisitos (tanto do usuário como da Fatec) abrangidos por essa sprint são:
- **RF 01:** Página principal - Home
- **RF 02:** Página - Pegada Ecológica
- **RF 03:** Página - Contato
- **RF 04:** Página - Login
- **RF 05:** Página - Sobre
- **RNF 01:** Utilizar JavaScript, HTML e CSS.
- **RNF 02:** Utilizar banco de daos NoSQL
- **RNF 04:** Responsividade
- **RNF 05:** Acessibilidade
- **RNF 06:** Compatibilidade

<span id="entregas">
        
## Entregas
Para entregas da sprint, tivemos os artefatos SCRUM validados, como Backlog do Produto, Backlog das Sprints e User Stories, através de comunicação direta entre o P.O. e o Scrum Master. Para observar esses artefatos, acesse [este link](https://dev.azure.com/felipevieira31/EcoVoucher).

Para extrair e entender as necessidades do usuário, foi construído um protótipo inicial no Figma, criando a identidade visual e design do sistema e apresentando para validação com alguns usuários, para visualizar o protótipo acesse [este link](https://www.figma.com/proto/6frOdD60Vkzfjw1AgnzLem/EcoVoucher?type=design&node-id=1-16&t=WoD44lI3FaHwzFPu-1&scaling=scale-down&page-id=0%3A1&starting-point-node-id=1%3A16&mode=design), onde o resultado deste protótipo, escrito utilizando Angular e com a integração das funcionalidades acordadas para a primeira sprint pode ser observado a seguir:

<div align="center">

![demo](./demo.gif)
</div>

Este protótipo valida a entrega dos requisitos confirmados para a sprint, onde suas descrições podem ser checadas a seguir:

### RF 01: Página Principal - Home

Este requisito se trata de uma página web com botões interativos e dinâmicos com rotas para outras páginas de conteúdo, foi desenvolvida na primeira etapa do projeto e refinada na Sprint 1.

### RF 02: Página - Pegada Ecológica

Este requisito se trata de uma página web com informações sobre o que é a pegada ecológica, um formulário para o usuário realizar o input de seus dados e o retorno da pontuação da pegada ecólogica desse usuário, bem como um comparativo dos países referência no quesito.

    
→ [Voltar ao topo](#topo)

<span id="metricas">
    
## :chart_with_upwards_trend: Métricas do time
Em prol de um melhor aproveitamento das habilidades de cada integrante, o time foi separado em duas frentes: frontend e backend, onde, na primeira sprint, o time de frontend ficou responsável pela confecção do protótipo, projeto frontend e integração de funcionalidades enquanto o time de backend ficou responsável pela criação dos microsserviços necessários e pesquisas sobre o tema do desafio. 
- O acompanhamento de atividades, de responsabilidade da Scrum Master, se encontra na imagem adiante, que contém o gráfico Burndown gerado pela equipe (onde o eixo X são os dias trabalhados na sprint e os valores do eixo Y representam as entregas e esforços realizados com o passar do tempo), incluindo as atividades desenvolvidas e seus responsáveis.
    
<div align="center">
    
![Burndown Chart](https://user-images.githubusercontent.com/69374340/163472803-4912e725-f05c-4cdc-84bc-29ae2953f401.png)
</div>
    
<span id="links">
    
## :link: Links úteis

- Site do projeto: [https://help-duck.netlify.app/](https://help-duck.netlify.app/) (usuário exemplo - email: `user@gmail.com`, senha: `1357`)
- Tags geradas em cada repositório que simbolizam o fim da 1ª sprint:
  - Repositório do site: [clique aqui para acessar "help-duck-web"](https://github.com/The-Bugger-Ducks/help-duck-web)
  - Microsserviço de autenticação: [clique aqui para acessar "help-duck-authentication"](https://github.com/The-Bugger-Ducks/help-duck-authentication)
  - Microsserviço de usuários: [clique aqui para acessar "help-duck-users-microservice"](https://github.com/The-Bugger-Ducks/help-duck-users-microservice)
  - Microsserviço de chamados: [clique aqui para acessar "help-duck-requests"](https://github.com/The-Bugger-Ducks/help-duck-requests)
