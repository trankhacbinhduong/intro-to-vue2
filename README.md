# `intro-to-vue2`
Learn basics about Vue2

## `The Vue Instance`
```ts
const vue = new Vue({ // root of every Vue application, reactive
  el: '#app', // plugs into an element in the DOM
  data: { // using the mustache-like syntax {{ }} display data
    title: 'Hello World!', 
  },
  ...options
})
```
