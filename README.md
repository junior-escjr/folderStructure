# folderStructure

```
.root or theme project
├── gulp/
|   ├── node_modules/
|   ├── tasks/
|   |   ├── clone-file.js
|   |   ├── concat-min-js.js
|   |   ├── sass.js 'converte o sass para css e minifica'
|   |   └── watch.js
|   |
|   ├── Gulpfile.js
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