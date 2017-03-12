# step-manager

> A Vue.js project

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build
```

For detailed explanation on how things work, consult the [docs for vue-loader](http://vuejs.github.io/vue-loader).



шаг - враппер
каждый шаг может содержать сколько угодно вложеных шагов
Каждый шаг с уникальным глобальным id и порядковым id на своем уровне
Подвязка id шагов на роутер.
состояния process|complete
Переход по умолчанию на следующий шаг текущего уровня
Кастомный переход по id шага
Шаг с вложенными шагами готовит данные для вложенных шагов и по готовности данных проваливается на первый вложеный шаг
