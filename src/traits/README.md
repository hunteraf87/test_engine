# Миксины

Функция mixin, делает "глубокое" расширение объекта заданными миксинами. Возвращает при этом новый объект.

```js
// {a: {b: 42, c: 2, e: 7}, j: 2}
const res = mixin({a: {b: 1, c: 2}}, {a: {b: 42, e: 7}}, {j: 2})
```
