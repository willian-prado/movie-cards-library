## Projeto Movie Cards Library

> Primeiro projeto do módulo de Front-end do curso de desenvolvimento web da Trybe.

**Contexto**

No bloco desse projeto somos introduzidos ao React e aqui praticamos alguns de seus conceitos básicos: 
componentes, props e componentização de páginas.

**Objetivo do projeto**

Criar uma biblioteca de cartões de filmes utilizando React. A página deverá possuir um cabeçalho e uma lista de cartões.
Cada cartão representa um filme e possui uma imagem, título, subtítulo, sinopse e avaliação.

**Principais habilidades desenvolvidas nesse trabalho:**

  - Inicializar um projeto em **React**
  - Utilizar JSX no **React**
  - Utilizar o **ReactDOM.render** para renderizar elementos numa página web
  - Utilizar o `import` para usar código externo junto ao seu
  - Criar componentes **React** corretamente
  - Fazer uso de `props` corretamente
  - Fazer composição de componentes corretamente
  - Criar múltiplos componentes dinamicamente
  - Utilizar **PropTypes** para checar o tipo de uma prop no uso de um componente
  - Utilizar **PropTypes** para garantir a presença de props obrigatórias no uso de um componente

**Tecnologias utilizadas**

- <a href="https://www.w3.org/html/"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" title="HTML5" align="center" height="35"/> - HTML</a> 
- <a href="https://www.w3schools.com/css/"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" title="CCS3" align="center" height="35"/> - CSS</a>
- <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" title="JavaScript" align="center" height="30"/> - JavaScript</a>
- <a href="https://reactjs.org/"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" title="React" align="center" height="35"/> - React</a> 

---

### Lista de requisitos propostos pela Trybe:

#### Obrigatórios

**1 - Crie um componente `<Header />`**

Criar um componente que represente o cabeçalho da página.

**2 - Renderize um texto no `<Header />`**

O texto deverá estar dentro de uma tag `h1`, que por sua vez deve estar dentro de uma tag `header`

**3 - Crie um componente `<MovieList />`**

Crie um componente que represente toda a área com os cartões de filmes. `<MovieList />` deve receber uma prop `movies`, que é um array de objetos com informações de um filme.

**4 - Renderize componentes `<MovieCard />` dentro de `<MovieList />`**

`<MovieList />` deve renderizar um componente `<MovieCard />` para cada objeto contido no array recebido na prop `movies`.

**5 - Passe uma key para cada `<MovieCard />` renderizado**

`<MovieList />` deve renderizar `<MovieCard />`s de forma dinâmica. Ou seja, deve utilizar a função `map` para renderizar uma lista. Cada componente `<MovieCard />` deve receber uma prop `key` com o nome do filme.

**6 - Crie um componente `<MovieCard />`**

Crie um componente que represente um cartão de filme. `<MovieCard />` deve receber uma prop `movie`. Essa prop será um objeto, contendo as propriedades, `title`, `subtitle`, `storyline`, `imagePath` e `rating`.

**7 - Renderize a imagem do filme dentro de uma tag `img`**

`<MovieCard />` deve renderizar uma tag `img`, tendo como atributo `src` o valor da propriedade `imagePath` do objeto recebido como prop.

**8 - Renderize o título do filme dentro de uma tag `h4`**

`<MovieCard />` deve renderizar o título do filme dentro de uma tag `h4`. O título está contido na propriedade `title` do objeto recebido como prop.

**9 - Renderize o subtítulo do filme dentro de uma tag `h5`**

`<MovieCard />` deve renderizar o subtítulo do filme dentro de uma tag `h5`. O subtítulo está contido na propriedade `subtitle` do objeto recebido como prop.

**10 - Renderize a sinopse do filme dentro de uma tag `p`**

`<MovieCard />` deve renderizar a sinopse do filme dentro de uma tag `p`. A sinopse está contida na propriedade `storyline` do objeto recebido como prop.

**11 - Crie um componente `<Rating />`**

Crie um componente que represente a avaliação de um filme.

**12 - Renderize a nota de um filme dentro de `Rating`**

`<Rating />` deve renderizar a nota do filme recebido na prop `rating` dentro de um elemento com a classe `rating`.

**13 - Renderize o componente `<Rating />` dentro de `<MovieCard />`**

`<MovieCard />` deve renderizar um componente `<Rating />`.

**14 - Passe como prop para o componente `<Rating />` o atributo `rating`**

`<MovieCard />` deve passar para o componente `<Rating />` uma prop chamada `rating`. O valor dessa prop é a propriedade `rating` do objeto recebido na prop `movie`.

**15 - Crie um componente `<App />`**

O componente `<App />` deve renderizar um componente `<Header />`.

**16 - Renderize `<MovieList />` dentro do componente `<App />`**

O componente `<App />` deve renderizar um componente `<MovieList />`, passando como prop `movies` a lista de filmes contida no arquivo `data.js`. Para isso, você precisará importar `data.js` dentro de `App.js`.

**17 - Adicione PropTypes a todos os componentes**

Todos os componentes que recebem props devem ter suas proptypes corretamente declaradas. O ESLint checa automaticamente declaração de proptypes.
