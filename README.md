# REPOSITÓRIO DE ESTUDOS DE SASS

## Para instalar usando o NPM
```
npm install -g sass
```
## Processando o arquivo Scss para css 

```
sass _cdn/scss/style.scss  _cdn/css/style.css
```

## Processando vários arquivos
```
sass _cdn/scss:_cdn/css
```

## Automatizando o sass
```
sass _cdn/scss:_cdn/css --watch
```
Este comando faz com que o sistema fique sendo monitorado pelo sass.

## Automatizando o sass agora com os arquivos comprimidos
```
sass _cdn/scss:_cdn/css --watch --style=compressed
```
Este comando deve ser evitado na camada de desenvolvimento devido a demora de compilação.