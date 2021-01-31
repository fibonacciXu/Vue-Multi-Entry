# multi-entry-vue

> Multi entry vue demo

multi-entry-vue
├── build
│   ├── build.js
│   ├── check-versions.js
│   ├── logo.png
│   ├── utils.js
│   ├── vue-loader.conf.js
│   ├── webpack.base.conf.js
│   ├── webpack.dev.conf.js
│   └── webpack.prod.conf.js
├── config
│   ├── dev.env.js
│   ├── index.js
│   └── prod.env.js
├── entries
│   ├── entry1
│   │   ├── router
│   │   │   └── index.js
│   │   ├── store
│   │   │   └── index.js
│   │   ├── App.vue
│   │   ├── index.html
│   │   └── main.js
│   ├── entry2
│   │   ├── router
│   │   │   └── index.js
│   │   ├── store
│   │   │   └── index.js
│   │   ├── App.vue
│   │   ├── index.html
│   │   └── main.js
│   └── entry3
│       ├── router
│       │   └── index.js
│       ├── store
│       │   └── index.js
│       ├── App.vue
│       ├── index.html
│       └── main.js
├── src
│   ├── assets
│   │   └── logo.png
│   ├── common
│   │   └── CommonTemplate.vue
│   └── components
│       ├── HelloWorld.vue
│       ├── test1.vue
│       ├── test2.vue
│       └── test3.vue
├── static
├── README.md
├── index.html
└── package.json

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
