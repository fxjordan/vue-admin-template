# Vue Admin Template

The project is configured by Vue CLI with the following additional libraries:

- PrimeVue (rich UI component library, see https://primefaces.org/primevue/)
- PrimeIcons
- PrimeFlex (CSS utility library, https://primefaces.org/primevue/showcase/#/primeflex)

On top of this, we adopted the [Sakai Admin Template for Vue](https://github.com/primefaces/sakai-vue)
into the project to be used as a copy-paste source for rapid admin UI prototyping.
The code is equivalent to the live preview available at [Sakai Vue](https://www.primefaces.org/sakai-vue)
See https://github.com/primefaces/sakai-vue for the original template code.


### Vue CLI config
```
{
  "useTaobaoRegistry": false,
  "packageManager": "yarn",
  "presets": {
    "BUDDY Admin": {
      "useConfigFiles": true,
      "plugins": {
        "@vue/cli-plugin-babel": {},
        "@vue/cli-plugin-typescript": {
          "classComponent": false,
          "useTsWithBabel": true
        },
        "@vue/cli-plugin-router": {
          "historyMode": true
        },
        "@vue/cli-plugin-vuex": {},
        "@vue/cli-plugin-eslint": {
          "config": "base",
          "lintOn": [
            "save"
          ]
        }
      },
      "vueVersion": "3",
      "cssPreprocessor": "dart-sass"
    }
  }
}
```

## Project setup
```
yarn install
```

### Compiles and hot-reloads for development
```
yarn serve
```

### Compiles and minifies for production
```
yarn build
```

### Lints and fixes files
```
yarn lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
