# Minha trilha de aprendizado

## Irei mostrar minha trilha de estudo e minhas conquistas aqui

* Quarta, 06, Dezembro de 2023
* Estou estudando de acordo com o: [Backend Developer Roadmap: What is Backend Development?](https://roadmap.sh/backend)

## Como funciona a internet?

[Introdução a Redes: Como Dados viram Ondas? | Parte 1 - YouTube](https://youtu.be/0TndL-Nh6Ok?si=J7l1NY4rs0Z2eQKh)

> ### Dados e ondas

* ##### Ondas
  
  <img title="" src="https://cdn.kastatic.org/ka-perseus-images/162fdc69c05f43654aabc5f36714446782a4ccb5.png" alt="Ondas" width="525">
  
  * Ondas de alta frequencia
    
    * Ondas de alta frquencia sao aquelas que tem um vale (crista ao contrario) maior e duram mais tempo
  
  * Ondas de baixa frequencia
    
    * Sao aquelas que tem um vale menor e um intervalo curto entre a crista (imagem acima) das ondas
  
  * [Luz: ondas eletromagnéticas, espectro eletromagnético e fótons (artigo) | Khan Academy](https://pt.khanacademy.org/science/physics/light-waves/introduction-to-light-waves/a/light-and-the-electromagnetic-spectrum))

* ##### Dados Digitais
  
  <img title="Bits" src="https://w7.pngwing.com/pngs/331/952/png-transparent-binary-number-computer-icons-binary-file-others-miscellaneous-text-rectangle.png" alt="BITS" width="236">
  
  - Zero significa desligado ou falso
  
  - Um significa ligado ou verdadeiro

* ##### Modulacao
  
  * Transforma os dados da forma digital para a forma fisica ou seja 0 e 1 para Ondas
  
  * Envia por meios como:
    
    * Cabos ( Fibra Optica, Cobre)
    
    * Radio ( Wi-Fi )
- ##### Demodulacao
  
  - Transforma os dados da forma fisica ( Ondas ) para a forma digital ( 0 e 1 )
  
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

> O que e o "S" de HTTPS?
> 
> Estudando...

## Como funciona os navegadores?

> O que eu sei: Os navegadores sao ferramentas criadas para processar os dados recebidos da internet via HTTP, essas tecnologias sao criadas para receber, processar o codigo nas linguagens de formatacao HTML e CSS, e processar os algoritmos escritos em Javascript (Linguagem utilizada na maioria senao em todos os navegadores)
