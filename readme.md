# **Ignite Challenges - Chapter II, challenge I**

Este repositório tem como intuito colocar em prática os conceitos de hooks e contexts do ReactJS.

O desafio em questão, era de implementar a funcionalidade de carrinho de compras na aplicação, onde deveria lidar com as funções de adicionar, remover e adicionar items ao carrinho.

## Instalação de dependências

Antes de rodar a aplicação deverá ter instalado e configurado previamente o <a href="https://nodejs.org/en/">NodeJS</a> e <a href="https://yarnpkg.com/">Yarn</a>. 

Para instalar as dependências do projeto, digite a linha de comando abaixo:

`$ yarn`

## Rodando testes com JEST

Para testar a aplicação e todas as funcionalidades da aplicação, foi criado uma rotina de testes para verificar ses o funcionamento da aplicação ocorre como deveria.

Para rodar os testes, basta aplicar o seguinte comando no terminal:

`$yarn test`

O resultado será semelhandte ao da imagem abaixo.

![print-tests](https://user-images.githubusercontent.com/58368716/156228120-8fbb9a66-5c5d-49a4-9592-70c39c1060f6.png)


## Rodando a aplicação

Por fim, para exibir a aplicação é preciso executar dois servidores, já que a aplicação conta com um API Faker para listar e lidar com produtos, estoques, etc. Primeiro, execute a API Fake com o comando:

`$ yarn server`

Depois execute o comando para iniciar a aplicação React:

`$ yarn start`

O Resultado esperado será esse:


https://user-images.githubusercontent.com/58368716/156228266-6c9ae703-88e2-4cb2-8cc5-6b62c5565e94.mp4

