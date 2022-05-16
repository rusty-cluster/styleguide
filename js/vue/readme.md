## Conventions

### script
* Vue 3, [composition api](https://vuejs.org/api/sfc-script-setup.html) and Vite 
* [Pinia](https://vueschool.io/lessons/introduction-to-pinia) as store
* [ESlint](/js/vue/.eslintrc.js), Stylelint
* Test suite with [vitest](https://github.com/vitest-dev/vitest), vue-test-utils, [msw](https://github.com/mswjs/msw)
* [configuration via ENV variables](https://12factor.net/config)
* alias `@` to `./src/`

### style
* [BEM](https://css-tricks.com/bem-101/) with flexboxes and CSS Grid over UX frameworks
* [SugarSS](https://github.com/postcss/sugarss) for indent-based css
* ID selectors and scoped styles prohibited because of BEM, to reduce cognitive overhead
* [woff2 fonts](https://caniuse.com/woff2)

### template
* [Pug](https://html-to-pug.com/) for indent-based html

## [Boilerplate](https://github.com/rusty-cluster/vue-boilerplate)
  
```
npm create vite@latest my-vue-app -- --template vue
```

## Anti-patterns

* Nuxt is redundant cause Vue 3 has built-in ssr
