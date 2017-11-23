# folderStructure

Exemplo abaixo é de como ficará a organização das pastas no projeto com os arquivos em suas respectivas pastas.

```
.root or theme project
├── gulp/
|   ├── node_modules/
|   ├── tasks/
|   |   ├── concat-js.js
|   |   ├── concat-sass.js
|   |   ├── min-css.js
|   |   ├── min-js.js
|   |   └── watch.js
|   |
|   ├── gulpfile.js
|   └── package.json
|
├── src/
|   ├── js/
|   └── sass/
|       ├── base/
|       |   ├── fonts/
|       |   |   └── nome_da_fonte/	'Para ficar organizado colocar a fonte dentro de pastas com seu respectivo nome'
|       |   |
|       |   ├── _fonts.scss
|       |   └── _reset.scss
|       |
|       ├── helpers/
|       |   ├── mixins/
|       |   |   ├── _grid.scss
|       |   |   └── _micro-mixins.scss
|       |   |
|       |   ├── _mixins.scss
|       |   ├── _variables-grid.scss
|       |   └── _variables.scss
|       |
|       ├── layout/
|       |   ├── _grid.scss
|       |   └── _main.scss
|       |
|       ├── libs/
|       └── all.scss
|
├── static/
|   ├── css/    'receberá o arquivo final do css'
|   ├── fonts/
|   ├── js/     'receberá o arquivo final dos js'
|   └── images/
|									
├── .gitignore	
└── README.md
```

#### Gulp Boilerplate
- [Link para o repositório](https://github.com/junior-escjr/gulp-boilerplate)