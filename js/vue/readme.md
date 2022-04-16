## Conventions

* Vue 3, composition api and Vite 
* [Single file components](https://vuejs.org/guide/scaling-up/sfc.html)
* [Pinia](https://vueschool.io/lessons/introduction-to-pinia) as store
* pug for indent-based html
* PostCSS + SugarCSS for indent-based css
* [BEM](https://css-tricks.com/bem-101/) with flexboxes and CSS Grid over UX frameworks
* ID selectors and scoped styles prohibited because of BEM, to reduce cognitive overhead
* [ESlint without prettier](https://eslint.org/docs/rules/indent), Stylelint
* Test suite with [vitest](https://github.com/vitest-dev/vitest), vue-test-utils, [msw](https://github.com/mswjs/msw)
* [woff2 fonts](https://caniuse.com/woff2)
* [configuration via ENV variables](https://12factor.net/config)
* Nuxt is redundant cause Vue 3 has built-in ssr

## Boilerplate
  
```
npm create vite@latest my-vue-app -- --template vue
```
