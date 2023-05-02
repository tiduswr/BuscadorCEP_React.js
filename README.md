# Buscador de CEP

Este projeto é um buscador de CEP simples, feito com React. Ele permite que o usuário pesquise por um endereço a partir de um CEP válido.

## Como executar o projeto

Para executar o projeto, é necessário ter o Node.js instalado na máquina. Em seguida, execute os seguintes passos:

1. Clone este repositório em sua máquina
2. Abra o terminal na pasta raiz do projeto
3. Execute o comando `npm install` para instalar as dependências
4. Execute o comando `npm start` para iniciar o servidor local
5. Abra o navegador e acesse `http://localhost:3000`

## Funcionalidades

O projeto possui uma única página com um campo de busca e um botão de pesquisa. Ao digitar um CEP válido e clicar no botão de pesquisa, o aplicativo faz uma requisição à API do ViaCEP (https://viacep.com.br/) para obter informações do endereço correspondente ao CEP digitado. Se a busca for bem-sucedida, as informações do endereço são exibidas na tela.

Se o usuário digitar um CEP inválido ou deixar o campo em branco, o aplicativo exibe uma mensagem de erro.

## Estrutura do código

O código do projeto está dividido em componentes React, que são responsáveis por exibir as diferentes partes da interface. O componente principal é o `App`, que controla o estado do aplicativo e faz a chamada à API do ViaCEP.

Os estilos da página estão definidos no arquivo `styles.css`.

O arquivo `api.js` contém a definição da função `get` que faz a chamada à API do ViaCEP utilizando a biblioteca `axios`.

## Conclusão

Este é um projeto simples, mas que demonstra como é possível utilizar o React para criar uma aplicação que consome uma API externa e exibe informações para o usuário.