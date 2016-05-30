---
order: 9
title: Selectors
---

* > This tip needs to be translated. [Contribute.](https://github.com/zenorocha/browser-diet/blob/master/src/documents/jquery/es/selectors.html.md)

Los selectores son unos de los asuntos más importantes en el uso de jquery. Hay muchas vías de seleccionar un elemento del DOM, pero no significa que todas tengan el mismo comportamiento, puedes seleccionar un elemento usando clases, IDs or métodos(methods) como 'find()', 'children()'.

Entre todos ellos, seleccionar un ID es la vía más rápida porque está basada en una operación nativa del DOM.

```js
$("#foo");
```

*[> Resultados en JSPerf](http://jsperf.com/browser-diet-jquery-selectors)*
