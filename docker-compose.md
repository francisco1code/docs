## Docker compose
**Nesse arquivo irei mostra como iremos usar o docker-compose em nosso projeto.**

Docker Compose é o orquestrador de containers da Docker. E como funciona um orquestrador em uma orquestra? Ele rege como uma banda deve se comportar/tocar durante uma determinada apresentação ou música.
Com o Docker Compose é a mesma coisa, mas os maestros somos nós! Nós que iremos reger esse comportamento através do arquivo chamado docker-compose.

[Saiba mais sobre docker-compose](https://docs.docker.com/compose/)

### Aplicação no projeto
Ele vai gerenciar a conexão entre nosso conteineres, depois que for configurado iremos usar apenas 2 comandos para o desenvolvimento em nosso projeto.

* Construir a imagem do compose

  `docker-compose build`
  
* Subir o compose

    `docker-compose up`
