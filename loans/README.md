## Buildpacks — Gerar imagem Docker automaticamente 
O Spring Boot possui suporte nativo a Cloud Native Buildpacks, permitindo gerar imagens Docker sem precisar escrever manualmente um Dockerfile. 

Para construir a imagem da aplicação, execute o comando abaixo na raiz do projeto:
```shell
    mvn spring-boot:build-image
```