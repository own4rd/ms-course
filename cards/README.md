# Jib — Build de imagem Docker sem Dockerfile

Jib é um plugin do Google que permite criar imagens Docker diretamente a partir do Maven ou Gradle, sem precisar de Docker instalado localmente e sem precisar de Dockerfile.

Com ele, a build da imagem é rápida, reprodutível e pode ser enviada diretamente para o Docker Hub ou outro registry.

```shell
mvn compile jib:dockerBuild
```