# Projeto Marvel API

![image](https://upload.wikimedia.org/wikipedia/commons/thumb/b/b9/Marvel_Logo.svg/2560px-Marvel_Logo.svg.png)

# Funcionalidades

### Lista de Personagens

A aplicação inicia na lista de personagens, com design baseado em cards, que renderizam nome e imagem do personagem provindas da API oficial da Marvel.

<img width="1000px" src="./demo/pagina-inicial.png">

### Busca de personagem por nome

No topo da página, há uma barra de pesquisa onde pode ser buscado um personagem pelo nome, utilizando um parâmeto da API.

<img width="1000px" src="./demo/busca-por-nome.gif">

### Modal contendo detalhes do personagem

Ao clicar em um card, um modal contendo nome, imagem, descrição e quadrinhos nos quais o personagem aparece renderiza na tela do usuário. Modal foi feito utilizando a biblioteca de UI do próprio Angular, o Angular Material. 

<img width="1000px" src="./demo/detalhes-dos-personagens.gif">

Ao clicar no "MORE" o usuario sera redirecionado ao site da marvel apresentando mais quadrinhos referente ao personagem buscado.

# Tecnologias utilizadas para o desenvolvimento do projeto

![image](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![image](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![image](https://img.shields.io/badge/Sass-CC6699?style=for-the-badge&logo=sass&logoColor=white)
![image](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![image](https://img.shields.io/badge/Jasmine-8A4182?style=for-the-badge&logo=Jasmine&logoColor=white)

# Projeto está na vercel 

O projeto está hospedado na vercel, <a href="https://valinor-marvel-api.vercel.app/" target="_blank">clicando aqui</a>, você será redirecionado ao projeto final. Caso não funcione, aqui está o link: https://valinor-marvel-api.vercel.app/

# Princípios de Engenharia de Software 

Neste projeto, utilizei o princípio de SRP - (Single Responsibility Principle), buscando dar a cada componente do Angular uma única responsabilidade, facilitando o uso e deixando o código organizado.

# Porque você optou pela tecnologia X e não a Y

Optei por fazer o projeto em Angular, pois foi a minha primeira framework aprendida junto ao Field Academy e também pela própria Field Control já fazer uso dela.

# Desafios encontrados e como foi resolvido 

Primeiramente, iniciei o projeto logo no começo dos estudos com Angular. Com isso, obtive alguma dificuldade com os components, porém, com bastante prática e dedicação, consegui ultrapassar essa barreira e comecei a organizar os components. Logo depois, tive dificuldade na parte da conexão com a API da Marvel, pois ela exige que o dev utilize uma hash MD5 para acessar os dados. Após algumas pesquisas e leitura da documentação da API, consegui fazer. Também não foi preciso fazer requisição à API por ID, pois no JSON inicial já vêm todas as informações. Quanto menos requisição à API, melhor. Além disso, o modal para apresentar os detalhes dos personagens, utilizado com o próprio UI do Angular Material, foi outra dificuldade, pois ainda estou em fase de aprendizado. Porém, consegui fazer com base no curso de Angular da Udemy e bastante pesquisas por fora. Já os testes foram bem complexos para mim, mas consegui implementar da melhor maneira possível com o Jasmine do Angular.
Enfrentei vários desafios ao fazer o projeto, porém, com o impulso dado no Field Academy, com dedicação e pondo bastante a mão na massa, eu consegui vencer mais essa barreira e estou muito feliz comigo mesmo e sei que sou capaz de resolver os problemas.

# O que poder ser melhorado e como fazer 

Com base nos meus estudos, vi que com o Angular é possível fazer muitas coisas a mais no projeto, porém decidi fazer algo mais simples, mas que tenha tudo o que é pedido no desafio da melhor maneira possível, com um código organizado. Futuramente, pretendo fazer uma paginação, colocando uma página inicial separando melhor os personagens e as informações por página, melhorar a questão da responsividade e adicionar algumas features novas. Também utilizar este projeto como base para consumir outras APIs e fazer projetos diferentes.

# Sobre mim 

Meu nome é Victor Job, tenho 22 anos, atualmente estou no último ano do curso de Engenharia da Computação na Faculdade UNILAGO. Desde criança, sempre amei a tecnologia. Com 10 anos, sob influência do meu pai, eu já mexia com as peças dos meus computadores. Sempre que tinha algum problema, eu tentava resolver, e as formatações eram sempre eu que fazia. Pelo que eu me lembro, nunca levei um computador para uma loja de informática. Era sempre eu que colocava a mão na massa, kkk.
Ao entrar na faculdade, eu comecei a conhecer um mundo novo de possibilidades com a programação. Mas, como trabalhei como técnico de informática no meu segundo e terceiro ano, não consegui progredir muito com meus estudos na área de desenvolvimento. Porém, no meu último semestre, tive mais contato com a programação na faculdade e fui gostando ainda mais da área. Com isso, tive que tomar a difícil decisão de parar de trabalhar como técnico para focar meus estudos na programação, que é o meu sonho.
Depois disso, veio o Field Academy, que foi um divisor de águas na minha vida, tanto profissional como pessoal, e que agregou muito aos meus estudos e me proporcionou ter a capacidade de fazer este projeto. E, claro, mesmo após o término do treinamento, estou sempre estudando, evoluindo cada dia mais e me desafiando a buscar o melhor possível.

# Contatos

<ul>
  <li>E-mail: victorsimon553@gmail.com</li>
  <li>Linkedin: https://www.linkedin.com/in/victor-job-2017b01ab/</li>
</ul>
