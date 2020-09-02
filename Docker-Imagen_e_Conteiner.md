## Imagens
### O que são Imagens Docker?
Pense nas imagens Docker como uma um VM(Virtual machine), Ela é o template (imagine uma classe em OOP) para rodar um container.
Você precisa baixar as imagens para rodar os containers ou pegar de algum lugar,e telas em seu repositório local para que o Docker utilize para criar um container quando você roda o docker run.
As imagens Docker ficam armazenadas no [Docker Hub](https://hub.docker.com/) e, para baixar uma, funciona igualzinho utilizar o Git com Github.

#### Comandos
 * Nesse exemplo iremos utilizar a imagem do Ubuntu
  
    `docker pull ubuntu`
 
 * Você pode listar as imagens baixadas em seu PC com o comando abaixo
 
    `docker images`
 
 * Agora iremos usar a imagem para subir um container
 
    `docker run -it ubuntu`
    
 Esse comando vai usar a imagem ubuntu, que você baixou em seu PC, para criar um novo Container, caso a imagem não exista no seu PC, o Docker vai baixar do Docker Hub e subir esse container automaticamente
 
  * Você também pode remover imagens locais com o comando
  
    `docker -rmi "Nome da imagem"`
 

## Containers
### O que é conteiner
 O Container é uma instância de uma Imagem em execução naquele momento
 
#### Comandos

  * Como subir um conateiner
        `docker run -it ubuntu`
   
  * Listar os Containers em execução com o comando
          `docker ps`
          
   * Como remover um Container
            `docker rm "nome do conteiner"
            

    
 
 
 **Ainda continua com duvidas sobre a teoria?, veja esse video pequeno para entender melhor [Dicionário do Programador](https://www.youtube.com/watch?v=-pUZBovqRcU)**
