# gulp-babel-sass-browersync

Este projeto foi criado para experimentar o funcionamento do [Gulp](https://gulpjs.com/) com:

- [Sass](https://sass-lang.com/)
- [Babel](https://babeljs.io/)
- [Browser-sync](https://browsersync.io/)

O objetivo deste projeto era criar um ambiente onde a aplicação fosse atualizada em tempo real
de acordo com as alterações feitas em um arquivo `.scss`, `.js` ou `.html`.

Para testar o ambiente, basta abrir o console desejado no diretório do projeto e executar comando:

```
$ npm install
```

Rodando o comando acima você irá instalar todas as dependencias necessárias para o desenvolvimento
dentro do ambiente.

Para começar a desenvolver e ter a sua aplicação atualizada automaticamente, basta abrir o console 
e executar o comando:

```
$ gulp watch
```

Rodando o comando acima, a aplicação será aberta em uma nova aba do seu navegador em um servidor
criado pelo **Browser-sync**. 

Para visualizar o arquivo `index.html` basta acessar a url:

```
http://localhost:3000/app/
```

ou

```
http://localhost:3000/app/index.html
```

Depois de tudo isso, basta realizar as alterações desejadas nos seus arquivos e visualizar a atualização automática.