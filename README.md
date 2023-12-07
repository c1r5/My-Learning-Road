# Minha trilha de aprendizado

## Irei mostrar minha trilha de estudo e minhas conquistas aqui

* Quarta, 06, Dezembro de 2023
* Estou estudando de acordo com o: [Backend Developer Roadmap: What is Backend Development?](https://roadmap.sh/backend)

## Como funciona a internet?

[Introdução a Redes: Como Dados viram Ondas? | Parte 1 - YouTube](https://youtu.be/0TndL-Nh6Ok?si=J7l1NY4rs0Z2eQKh)

> ### Dados e ondas

* ##### Ondas
  
  <img src="https://cdn1.byjus.com/wp-content/uploads/2022/05/Types-of-Waves-1.png" title="" alt="Ondas" width="375">
  
  * As cristas podem ser representadas pelo UM.
  
  * Os vales podem ser representados pelo ZERO
  
  * Comprimentos sendo o intervalo de ZEROs ou UMs

* ##### Modulacao
  
  * Transforma os dados da forma digital para a forma fisica ou seja Bits para Ondas
  
  * Envia por meios como:
    
    * Cabos ( Fibra Optica, Cobre)
    
    * Radio ( Wi-Fi )
- ##### Demodulacao
  
  - Transforma os dados da forma fisica ( Ondas ) para a forma digital ( Bits )
  
  - Decodifica os dados.

##### *Para garantir a seguranca dos dados durante a transmissao, eles sao criptografados utilizando o HTTPS([TLS](https://www.cloudflare.com/pt-br/learning/ssl/transport-layer-security-tls/))*

## O que e HTTP?

> O que eu sei: O http ou Hyper Text Transfer Protocol e um conjunto de regras para transferencia de conteudo entre dois computadores, onde os mesmo irao processar os dados transformando eles em uma forma humanamente legivel.

Esse conjunto de regras sao alguns parametros a serem passados, os principais de requisicao sao:

- Metodo 
  
  - POST (Uma forma de passar dados de forma que nao aparecam na URL)
  
  - GET    (Dados passados na URL)
  
  - PUT    (Uma solicitacao para atualizar dados no servidor)
  
  - DELETE ( Deletar dados no servidor )
  
  - HEAD  (Uma forma de solicitar o cabecalho antes de pedir o conteudo inteiro para otimizar)
    
    - [Métodos de requisição HTTP - HTTP | MDN](https://developer.mozilla.org/pt-BR/docs/Web/HTTP/Methods)

- URI ( URL e Parametros)
  
  - example.com/?chave=valor

- Cabecalhos ( Header )
  
  - Host (Definir o host do web site)
  
  - Origin ( A origem da requisicao )
  
  - Content-Type ( Tipo de conteudo a ser passado no corpo)

- Corpo
  
  - Dados do formato definido no Cabecalho Content-Type

## Como funciona os navegadores?

> O que eu sei: Os navegadores sao ferramentas criadas para processar os dados recebidos da internet via HTTP, essas tecnologias sao criadas para receber, processar o codigo nas linguagens de formatacao HTML e CSS, e processar os algoritmos escritos em Javascript (Linguagem utilizada na maioria senao em todos os navegadores)
