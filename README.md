# Teste p/ Desenvolvedor MJV

Propomos um teste unificado para a avaliação de desenvolvedores Frontend/Backend/Full-stack com base em diferentes tópicos que podem ser escolhidos de acordo com os conhecimentos do candidato. 

O objetivo do teste é montar parte(s) de um sistema de loja virtual e **atingir uma somatória de 100 pontos** entre funcionalidades e tópicos demonstrados. Portanto, não se preocupe em fazer todas as funcionalidades e tópicos listadas abaixo, foque nos que você tem mais conhecimento e facilidade. Sugerimos cerca de 2 funcionalidades a serem feitas para atingir a pontuação.

Sugestões de funcionalidades a serem desenvolvidas e as respectivas pontuações máximas em parênteses:
- Menu de Categorias  (20 pontos)
- Lista de produtos (vitrine) (50 pontos)
- Busca de produtos (30 pontos)
- Detalhe de Produto (30 pontos)
- Type-ahead (auto-complete) para busca de produtos (30 pontos)
- Carrinho de compras (50 pontos)
- Cadastro de usuário (30 pontos)
- Login (35 pontos)
- Página do usuário (20 pontos)
- Lista de produtos (administrativo) (35 pontos)
- Paginação (10 pontos p/ paginação client-side, 20 pontos p/ paginação server-side)
- Cadastro de produto (25 pontos)

Para desenvolvedores Frontend pode-se mockar os dados no front, mas a demonstração de consumo de APIs é recomendada.

Para desenvolvedores Backend pode-se fazer somente a API em GraphQL ou os endpoints REST c/ Swagger.

Para desenvolvedores Full-stack, é esperado uma aplicação web consumindo um backend em GraphQL ou Rest.

### Entregáveis

Nos envie um email com o(s) link(s) dos repositórios contendo os projetos e opcionalmente um link para a aplicação publicada. Cada repositório deve conter um arquivo README.md como este, explicando brevemente as funcionalidades realizadas, como rodar a aplicação, popular banco de dados etc e opcionalmente quais tópicos abordou. Caso queira publicar seu teste, sugerimos utilizar o **[Heroku](https://heroku.com.br)**, onde é possível criar publicar suas aplicações sem custo e com banco de dados Postgres/MongoDb.

Abaixo seguem os tópicos que gostariamos de ver de acordo com a stack e em parênteses o bônus máximo de pontuação a ser obtido ao atender o tópico. Queremos que nos mostre o seu melhor, então selecione as funcionalidades e tópicos que mais lhe darão oportunidade para mostrar os seus conhecimentos sem a necessidade de tornar o teste extenso.

## Tópicos Comums (Front/Back): 

**Geral**
- Demonstrar boa legibilidade de código (+10)
- Demonstrar domínio de lógica de programação (+10)
- Demonstrar conhecimento de programação orientada a objetos (+3)
- Demonstrar conhecimento de programação funcional (+10)
- Utilização de estruturas imutáveis de dados (+3)
- Utilização de scripts npm (+2)

**Javascript**
- Demonstrar uso de funcionalidades novas no Javascript (ex: async/wait, spread operators, arrow functions, template literals, etc) (+3)
- Documentação com JSDocs (+3)
- Encadeamento de Promises (+5)

**Typescript**
- Demonstrar conhecimento e aplicação de Typescript (interfaces, tipos, união/intersecção de tipos, literais, etc) (+10)
- Utilizar opções de compilação restritas (ex: strict: true) (+5)
- Utilizar opção de compilação *strictNullChecks* com uso de tipos null/undefined (+5)
- Utilização de type-guards (+3)
- Utilização de types auxiliares (ex: Required, Record, etc) (+3)
- Utilização de Generics (+3)

**Linter**
- Aplicar uso de linter p/ normalizar o estilo do projeto (ex: ESLint, TSLInt) (+5)

**Testes**
- Demonstrar conhecimento de testes unitários (+10)
- Demonstrar conhecimento de mock p/ dependências de classe(+5)
- Atingir bom nível de code-coverage com testes (+10)

**Git**
- Demonstrar boa atomicidade nos commits (ex: único commit por funcionalidade ou bugfix) (+5)
- Demonstrar bom uso de mensagens de commit (+5)
- Utilizar algum formato padrão de mensagens de commit (+5)

**Publicação**
- Publicação de frontend p/ acesso online (+5)
- Publicação de backend p/ acesso online (+15)

## Tópicos de Frontend: 
- Criação de aplicação web (+10)
- Uso de requisições HTTP (+10)

**HTML/CSS**
- Layout Visual (+25)
- Demonstrar boa aplicação de layout (+5)
- Demonstrar uso de layout responsível (+5)
- Demonstrar conhecimento de flex-box (+5)
- Demonstrar conhecimento de animações CSS (+5)
- Fazer uso de algum padrão de CSS (BEM, SMACSS) (+10)
- Utilizar e fazer uso de recursos de algum framework CSS (ex: SCSS, Stylus, Less, etc) (+5)

**UX**: 
- Demonstrar boa navegabilidade (+5)
- Utilizar animações/elementos para guiar a experiência do usuário (ex: Indicadores de carregamento, transições de estado/página) (+10)
- Configuração de Progressive-web-app (+10)

**Angular**
- Demonstrar boas práticas de arquitetura (+10)
- Utilizar rotas (+5)
- Utilizar módulos (+5)
- Utilizar módulos lazy-loaded (+5)
- Utilizar serviços (+5)
- Configuração e consumo de bibliotecas externas (ex. Angular Material) (+5)
- Demonstrar animações utilizando a API do Angular (+5)
- Utilizar biblioteca p/ gerenciamento de estado (ex: Apollo Client, NgRx, Akita, Angular-Redux, etc) (+15)
- Tuning de performance de componentes (+5)
- Configuração de interceptador de request (+5)

**RxJS**
- Demonstrar uso de operadores RxJS (ex. debounce de key strokes, retentativas de request) (+10)
- Demonstrar uso de Subjects (ex: armazenamento de estado) (+10)
- Demonstrar tratamento de erros (+5)

**React**
- Demonstrar boas práticas de arquitetura (+10)
- Utilização de functional components (+5)
- Utilização de React Hooks (+5)
- Utilização de Higher-Order-Components (+5)
- Utilização de pattern de container/presentational components (+5)
- Utilização de algum gerenciador de estado (Apollo Client, Redux, MobX, etc) (+15)
- Integração com outras bibliotecas (+5)
- Lazy-load de componentes (+5)
- Utilização com Typescript (+10)

## Tópicos de Backend:

**NodeJS/C#** 
- Criação de aplicação (+10)
- Uso de banco de dados relacional/não relacional (+10)
- Script p/ estrutura do banco (+15)
- Script p/ popular banco (+10)
- Utilização de middlewares (+5)
- Utilização de JSON Web Tokens p/ autenticação (+10)
- Validação de dados das requests (+5)
- Utilizar alguma ferramenta p/ auxilar o desenvolvimento (nodemon, node-dev, ts-node-dev, etc) (+3)

**GraphQL**
- Criação de endpoint GraphQL (+10)
- Construir operações de Query (+10 p/ query)
- Construir operações de Mutation (+10 p/ mutation)
- Construir operações de Subscription (+10 p/ subscription)
- Utilizar alguma união de tipo (+5)

**REST**
- Criação de endpoints REST p/ consumo do front (+5 p/ endpoint) 
- Documentar a API com uso de Swagger (+10)

**Docker**
- Configurar docker p/ as aplicações (+10)


### Ferramentas

Imagens de placeholder - http://lorempixel.com/

Mock de APIs 
- https://reqres.in/
- https://www.mocky.io/
- https://jsonplaceholder.typicode.com/
