# Burger Queen

LETÍCIA E MAIRÃ

## Índice

- [1. Preâmbulo](#1-preâmbulo)
- [2. Resumo do projeto](#2-resumo-do-projeto)
- [3. Objetivos de aprendizagem](#3-objetivos-de-aprendizagem)
- [4. Considerações gerais](#4-considerações-gerais)
- [5. Critérios de aceitação mínimos do
  projeto](#5-critérios-de-aceitação-mínimos-do-projeto)
- [6. Hacker Edition](#6-hacker-edition)
- [7. Dicas e leituras complementares](#7-dicas-e-leituras-complementares)
- [8. Checklist](#8-checklist)

---

## 1. Preâmbulo

[React](https://reactjs.org/), [Angular](https://angular.io/) e
[Vue](https://vuejs.org/) são alguns dos _frameworks_ e _bibliotecas_ de
JavaScript mais usados na área de desenvolvimento ao redor do mundo e existe uma
razão para isso. No contexto do navegador, [_manter a interface sincronizada com
o estado é difícil_](https://medium.com/dailyjs/the-deepest-reason-why-modern-javascript-frameworks-exist-933b86ebc445).

Ao eleger um _framework_ ou _biblioteca_ para nossa interface, nos apoiamos em
uma série de convenções e implementações _testadas_ e _documentadas_ para
resolver um problema comum a toda interface web. Isto nos permite concentrar
melhor (dedicar mais tempo) nas características _específicas_ de nossa
aplicação.

Quando escolhemos uma destas tecnologias não só importamos um pedaço de código
para reusar (o qual já é um grande valor por si só), mas também adotamos uma
**arquitetura**, uma série de **princípios de design**, um paradigma, algumas
**abstrações**, um **vocabulário**, uma **comunidade**, etc...

Como desenvolvedora Front-end, estes kits de desenvolvimento podem resultar em
uma grande ajuda para implementar rapidamente _features_ dos projetos em que
você for trabalhar.

## 2. Resumo do projeto

Desta vez temos um projeto 100% por demanda. Você sempre pode (e deve) fazer
sugestões de melhora e mudança, mas muitas vezes trabalhará em um projeto em que
primeiro deve se assegurar de cumprir os requisitos.

Um pequeno restaurante de hambúrgueres, que está crescendo, necessita uma
interface em que se possa realizar pedidos utilizando um _tablet_, e enviá-los
para a cozinha para que sejam preparados de forma ordenada e eficiente.

![burger-queen](https://user-images.githubusercontent.com/110297/42118136-996b4a52-7bc6-11e8-8a03-ada078754715.jpg)

Estas são as informações que temos do cliente:

> Somos **Burger Queen**, um fast food 24hrs.
>
> A nossa proposta de serviço 24 horas foi muito bem recebida e, para continuar a
> crescer, precisamos de um sistema que nos ajude a receber pedidos de nossos
> clientes.
>
> Nós temos 2 menus. Um muito simples para o café da manhã:
>
> | Ítem                  | Preço R\$ |
> | --------------------- | --------- |
> | Café americano        | 5         |
> | Café com leite        | 7         |
> | Misto Quente          | 10        |
> | Suco de fruta natural | 7         |
>
> E outro menu para o resto do dia:
>
> | Ítem                | Preço   |
> | ------------------- | ------- |
> | **Hambúrgueres**    | **R\$** |
> | Hambúrguer simples  | 10      |
> | Hambúrguer duplo    | 15      |
> | **Acompanhamentos** | **R\$** |
> | Batata frita        | 5       |
> | Anéis de cebola     | 5       |
> | **Bebidas**         | **R\$** |
> | Água 500ml          | 5       |
> | Água 750ml          | 7       |
> | Refrigerante 500ml  | 7       |
> | Refrigerante 750ml  | 10      |
>
> **Importante:** Os clientes podem escolher entre hambúrgueres de carne bovina,
> frango ou vegetariano. Além disso, por um adicional de R\$ 1,00 , eles podem
> adicionar queijo **ou** ovo.
>
> Nossos clientes são bastante indecisos, por isso é muito comum que eles mudem o
> seu pedido várias vezes antes de finalizar.

A interface deve mostrar os dois menus (café da manhã e restante do dia), cada
um com todos os seus _produtos_. O usuário deve poder escolher que _produtos_
adicionar e a interface deve mostrar o _resumo do pedido_ com o custo total.

![out](https://user-images.githubusercontent.com/110297/45984241-b8b51c00-c025-11e8-8fa4-a390016bee9d.gif)

## 3. Objetivos de aprendizagem

O objetivo principal é aprender a construir uma interface web usando React. Esse framework front-end ataca o seguinte problema: **como manter a interface e estado sincronizados**. Portanto, esta experiência espera familiarizá-la com o conceito de estado da tela, e como cada mudança no estado vai refletir na interface (por exemplo, toda vez que adicionamos um _produto_ para um _pedido_, a interface deve atualizar a lista de pedidos e o total).

Finalmente, a interface deve ser pensada específicamente para rodar em **tablets**.

## 4. Considerações gerais

**Trabalhe integralmente uma história de usuário antes de passar para a próxima.** Cumpra todas as histórias possíveis dentro do tempo especificado.

A lógica do projeto deve ser totalmente implementada em JavaScript (ES6 +). Neste projeto você deve usar [React](https://reactjs.org/).

O aplicativo deve ser um _Single Page App_. Os pedidos serão enviados por meio de um _tablet_,mas **não queremos um aplicativo nativo**, mas sim um aplicativo Web que seja **responsivo**.

Precisamos pensar bem sobre o UX para aqueles que vão receber os pedidos, o tamanho e a aparência dos botões, a visibilidade do estado atual do pedido, etc.

Você deve definir a estrutura das pastas e arquivos que considera necessários. Você pode estruturá-los de acordo com as convenções do React.

Está liberado o uso de bibliotecas de componentes e pré-processadores de CSS.

Você está livre para escolher o nome do seu restaurante.

Recomendamos que o deploy seja feito utilizando [Heroku](https://www.heroku.com/), [Netlify](https://www.netlify.com/) ou [Vercel](https://vercel.com/).

Para iniciar este projeto você terá que fazer um _fork_ e _clone_ deste repositório.

## 5. Critérios mínimos de aceitação do projeto

### Definição do produto

O [_Product Owner_](https://www.youtube.com/watch?v=7lhnYbmovb4) nos apresentou
este _backlog_ que é o resultado do seu trabalho com o cliente até hoje.

---

#### [História de usuário 1] Usuário deve ter seu perfil (login/senha) para acessar o sistema.

Eu como funcionário do restaurante quero entrar na plataforma e ver apenas a tela importante para o meu trabalho.

##### Critérios de aceitação

O que deve acontecer para satisfazer as necessidades do usuário?

- Criar login e senha.
- Registar tipo de usuário (cozinha / salão), login e senha.
- Entrar na tela correta para cada usuário.

##### Definição de pronto

O acordado abaixo deve acontecer para dizer que a história está terminada:

- Você fez _testes_ de usabilidade e incorporou o feedback do usuário.
- Você deu deploy de seu aplicativo.

---

#### [História de usuário 2] Garçom/Garçonete deve poder anotar o seu pedido

Eu como garçom/garçonete quero poder anotar o meu pedido saber o valor de cada
produto e poder enviar o pedido para a cozinha para ser preparado.

##### Critérios de aceitação

O que deve acontecer para satisfazer as necessidades do usuário?

- Anotar o nome e mesa.
- Adicionar produtos aos pedidos.
- Excluir produtos.
- Ver resumo e o total da compra.
- Enviar o pedido para a cozinha (guardar em algum banco de dados).
- Funcionar bem e se adequar a um _tablet_.

##### Definição de pronto

O acordado abaixo deve acontecer para dizer que a história está terminada:

- Você fez _testes_ de usabilidade e incorporou o _feedback_ do usuário.
- Você deu deploy de seu aplicativo.

---

#### [História de usuário 3] Chefe de cozinha deve ver os pedidos

Eu como chefe de cozinha quero ver os pedidos dos clientes em ordem, poder marcar que estão prontos e poder notificar os garçons/garçonetes que o pedido está pronto para ser entregue ao cliente.

##### Critérios de aceitação

- Ver os pedidos à medida em que são feitos.
- Marcar os pedidos que foram preparados e estão prontos para serem servidos.
- Ver o tempo que levou para preparar o pedido desde que chegou, até ser marcado como concluído.

##### Definição de pronto

- Você fez _testes_ de usabilidade e incorporou o _feedback_ do usuário.
- Você deu deploy de seu aplicativo.

---

#### [História de usuário 4] Garçom/Garçonete deve ver os pedidos prontos para servir

Eu como garçom/garçonete quero ver os pedidos que estão prontos para entregá-los rapidamente aos clientes.

##### Critérios de aceitação

- Ver a lista de pedidos prontos para servir.
- Marque os pedidos que foram entregues.

##### Definição de pronto

- Você fez _testes_ de usabilidade e incorporou o _feedback_ do usuário.
- Você deu deploy de seu aplicativo.
- Os dados devem ser mantidos intactos, mesmo depois que um pedido foi terminado. Tudo isso para poder ter estatísticas no futuro.

---

## 6. Hacker Edition

As seções chamadas Hacker Edition são opcionais. Se você terminou tudo e ainda sobrou tempo, faça essa parte. Assim você poderá aprofundar e exercitar mais sobre os objetivos de aprendizagem do projeto.

- Faça testes que cubram 70% de statements, functions, lines e branches.
- Configure o _linter_ (ESLint) no seu projeto.

---

## 7. Dicas e leituras complementares

### Primeros passos

- Para iniciar este projeto você terá que fazer um _fork_ e _clone_ deste repositório

- Crie um projeto usando `create-react-app`

- Leia a documentação da [Burger Queen API](https://lab-api-bq.herokuapp.com/api-docs/)

---

### Outros recursos

#### Framework / biblioteca

- [React](https://reactjs.org/)

#### React Hooks

- [React Hooks](https://reactjs.org/docs/hooks-intro.html)
- [Entendendo React Hooks](https://medium.com/@higornevesmarques/entendendo-react-hooks-2c0efae276a3)
- [React Hooks - Rocketseat](https://blog.rocketseat.com.br/react-hooks/)
- [Habemus React Hooks](https://willianjusten.com.br/habemus-react-hooks/)

#### Ferramentas

- [Babel](https://babeljs.io/)
- [webpack](https://webpack.js.org/)
- [React Router](https://reactrouter.com/web/guides/quick-start)
- [Axios](https://github.com/axios/axios)

#### Estilização

- [Pré-Processadores CSS - Definição](https://developer.mozilla.org/pt-BR/docs/Glossario/CSS_preprocessor)
- [Pré-Processadores CSS - Motivação](https://www.zup.com.br/blog/o-que-sao-pre-processadores-css)
- [Material-UI](https://material-ui.com/)
- [Aphrodite](https://github.com/Khan/aphrodite)
- [Styled Components](https://styled-components.com/)

#### Requisições com React

- [React + Fetch](https://jasonwatmore.com/post/2020/02/01/react-fetch-http-post-request-examples)
- [React + Axios](https://jasonwatmore.com/post/2020/07/17/react-axios-http-get-request-examples)

#### Testando requisições

- [Insomnia](https://insomnia.rest/)
- [Postman](https://www.postman.com/)

#### Testes

- [React Testing Library](https://testing-library.com/docs/react-testing-library/intro/)
- [Jest](https://jestjs.io/)

#### Configuração de ESLint

- [ESLint + Prettier](https://henriquetavares.com/pt-br/setting-eslint-on-reactjs-and-react-native/)

#### Deploy

- [Opções de deploy com Create React App](https://create-react-app.dev/docs/deployment)
- [Deploy + Netlify (vídeo)](https://drive.google.com/file/d/1hzlB8dl4m0OnLLY2-WpjSLcU7eYTURRk/view)
- [Deploy + Heroku (vídeo)](https://drive.google.com/file/d/1eqx6yuwJnAU-R83ta89tgEem7ABZigNG/view)
- [Deploy + Vercel (vídeo)](https://drive.google.com/file/d/1Q9q1iVnRrWeEhGRns0r5OOeiqloQug8y/view)

---

## 8. Checklist

#### `README.md`

- [ ] Documentação do processo de design.
- [ ] Inclui informações para desenvolvedores (dependências, instalação, uso, testes...).

#### HU 1: Criar perfil

- [ ] Poder realizar cadastro com e-mail, senha e função.
- [ ] Poder realizar login com e-mail e senha.
- [ ] Redirecionar para a tela correta.

#### HU 2: Anotar pedidos

- [ ] Digitar o nome do cliente e mesa.
- [ ] Filtrar _menu_ para _café da manhã_ e _almoço/jantar_.
- [ ] Adicionar item ao pedido.
- [ ] Excluir item do pedido.
- [ ] Mostrar _resumo_ do pedido com todos os itens e o total.
- [ ] Enviar para a cozinha (isso deve salvar o pedido).

#### HU 3: Ver pedidos na cozinha

- [ ] Visualizar pedidos pendentes para produção.
- [ ] Marcar pedido como pronto para entrega.
- [ ] Ver histórico dos pedidos.

#### HU 4: Entrega de pedidos

- [ ] Visualizar pedidos pendentes para entrega.
- [ ] Marcar pedido como entregue ao cliente.

### UX

- [ ] Funciona bem em tablets.
- [ ] Fácil utilização em telas sensíveis ao toque.
- [ ] Status atual do pedido sempre visível enquanto fazemos um pedido.

### Hacker Edition

#### Testes

- [ ] 70% de cobertura de _statements_.
- [ ] 70% de cobertura de _functions_.
- [ ] 70% de cobertura de _lines_.
- [ ] 70% de cobertura de _branches_.

#### ESLint
