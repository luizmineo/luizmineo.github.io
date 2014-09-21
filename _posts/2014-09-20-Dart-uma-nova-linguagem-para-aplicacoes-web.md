---
layout: post
title: "Dart: Uma nova linguagem para aplicações Web"
---

Na verdade, [Dart](http://dartlang.org) já não é tão nova assim. A linguagem foi anunciada pela Google em 2011, e desde então vem sendo desenvolvida ativamente, tanto pela empresa, quanto pela comunidade de usuários que se formou ao seu redor. 

Dart é uma linguagem modular, orientada a objetos e com suporte a classes, que se destaca por possuir recursos como tipagem opcional, funções de primeira classe e closures. O site oficial possui um [excelente comparativo](https://www.dartlang.org/docs/synonyms/) com outras linguagens, como Java e Javascript, além de uma [detalhada documentação](https://www.dartlang.org/docs/dart-up-and-running/), [tutorials](https://www.dartlang.org/docs/tutorials/), [apresentações](https://www.dartlang.org/slides/) e [artigos](https://www.dartlang.org/articles/).

Criada para ser uma alternativa ao Javascript, Dart possui um compilador (dart2js) que permite a sua execução nos principais navegadores web, incluindo Firefox, Chrome, Safari, Opera e IE (a partir da versão 10), sem a necessidade de plugins. Porém, seu uso não está restrito apenas aos navegadores. Graças a sua máquina virtual (DartVM), ela também pode ser usado para criar aplicações servidoras.  

## Dart é usado em projetos reais?

A Google, segundo afirma, [utiliza a linguagem, juntamente com o framework AngularDart, em seu sistema interno de vendas](http://news.dartlang.org/2013/11/angular-announces-angulardart.html). A empresa também tem usado Dart no desenvolvimento do [Chrome Dev Editor](https://chrome.google.com/webstore/detail/chrome-dev-editor-develop/pnoffddplpippgcfjdhbmhkofpnaalpg), uma IDE para criação de aplicações web e extensões do Chrome. O vídeo abaixo é uma apresentação realizada durante o Google I/O 2014, onde desenvolvedores da Google demonstram como utilizaram o framework [Polymer.dart](https://www.dartlang.org/polymer/) na construção da IDE. 

<div class="embedded-content">
  <iframe width="560" height="315" src="//www.youtube.com/embed/NNLnTz6yIc4" frameborder="0" allowfullscreen></iframe>
</div>

Também na Google I/O 2014, os criadores do [Soundtrap](https://www.soundtrap.com/), falaram sobre porque escolheram Dart para construir sua ferramenta colaborativa de gravação e mixagem de áudio. A apresentação está disponível no vídeo abaixo.

<div class="embedded-content">
  <iframe width="560" height="315" src="//www.youtube.com/embed/PMH1vM-dSc0" frameborder="0" allowfullscreen></iframe>
</div>

Desde 2013, a Adobe oferece o [Toolkit for Dart](http://toolkitfordart.github.io/), uma extensão para o [Flash Professional CC](http://www.adobe.com/br/products/flash.html), que permite exportar aplicações para HTML5 usando Dart. A extensão utiliza o [StageXL](http://www.stagexl.org/), um framework que foi criado para facilitar o port de aplicações Flash para Dart, mas que acabou se tornando uma excelente ferramenta para criação de games e outras aplicações que fazem uso de gráficos 2D.

O [SecurityMonkey](https://github.com/Netflix/security_monkey), projeto open source da Netflix que monitora serviços hospedados na nuvem da Amazon, também é um exemplo de uso do Dart, que foi utilizado para construir sua interface web.

Além desses, existem vários outros casos de sucesso, que são [listados no site oficial](https://www.dartlang.org/community/who-uses-dart.html).

## Biblotecas e Frameworks

A plataforma Dart já conta com um grande número de bibliotecas e frameworks, graças aos esforços de seus mantenedores, e também da comunidade. 

O [Pub](https://pub.dartlang.org/) é o repositório central de pacotes Dart. Através dele, é possível baixar frameworks como o [AngularDart](https://angulardart.org/) e [Polymer.dart](https://www.dartlang.org/polymer/), ports dos conhecidos [AngularJs](https://angularjs.org/) e [Polymer](http://www.polymer-project.org/), respectivamente, e que são mantidos pela própria equipe de desenvolvimento do Dart.

Além de pacotes que facilitam a criação de aplicações que rodam no navegador, o Pub também possui várias bibliotecas para aplicações servidoras, como drivers para diversos bancos de dados, incluindo [MongoDB](https://pub.dartlang.org/packages/mongo_dart) e [PostgreSQL](https://pub.dartlang.org/packages/postgresql). Também há frameworks como o [Redstone.dart](http://redstonedart.org), para criação de serviços web, que aliás, é o framework que desenvolvo e mantenho desde fevereiro deste ano (portanto, sou meio suspeito para falar sobre ele...). 

## Dart vai ser adotado pelo mercado?

Ainda é cedo para dizer, mas acredito que Dart tem um futuro bastante promissor. Além disso, a linguagem trás muitas ideias boas e inovadoras, e eu diria que na pior das hipóteses, essas ideias servirão de inspiração, ou serão incorporadas por soluções futuras. Se você tem interesse em aplicações web e em novas tecnologias, recomendo fortemente dedicar um pouco do seu tempo para estudar a linguagem Dart. 

## Dart no Brasil

Infelizmente, ainda não temos uma comunidade de desenvolvedores ativa aqui no Brasil. Um dos objetivos deste blog é justamente contribuir para que uma comunidade se forme, oferecendo informações e tutoriais sobre Dart em português. Se você possui ideias, criticas ou sugestões a respeito, deixe seu comentário abaixo.