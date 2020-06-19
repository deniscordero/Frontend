- [Frontend](#frontend)
  - [1. Introducción al curso](#1-introducción-al-curso)
    - [Algúnos conceptos:](#algúnos-conceptos)
    - [¿Qué son y para qué nos sirven HTML y CSS?](#qué-son-y-para-qué-nos-sirven-html-y-css)
    - [DOM, CSSOM, Render Tree y el proceso de renderizado de la Web](#dom-cssom-render-tree-y-el-proceso-de-renderizado-de-la-web)
    - [5 tips para aprender CSS](#5-tips-para-aprender-css)

# Frontend

## 1. Introducción al curso

### Algúnos conceptos:

`Interconnected + Network -> Internet`

`Tim Berners-Lee -> World Wide Web -> www` *fundo* -> `W3C`

`H`yper
`T`ext
`T`ranfer
`P`rotocol`://`

```
http://
```

`U`niform `R`esourc `L`ocator

`H`yper `T`ext `M`arkup `L`anguaje

1994 -> CSS `C`ascade `S`tyle `S`heets

define la apariencia
Responsive Design

extensiones
archivo.html --> Estructura
estilos.css --> Estilos

### ¿Qué son y para qué nos sirven HTML y CSS?

>`HTML`: Es un **lenguaje** de marcado usado para decirle a tu navegador cómo estructurar las páginas web que visitas. No es un lenguaje de programación.
>>[HTML reference](https://htmlreference.io/)

>`CSS`: Es un lenguaje que nos permite crear páginas web con un diseño agradable para los usuarios. Tampoco es un lenguaje de programación.
>>[CSS Reference](https://cssreference.io/)

### DOM, CSSOM, Render Tree y el proceso de renderizado de la Web

`DOM`: Document Object Model. Es una transformación del código HTML escrito por nosotros a objetos entendibles para el navegador.

`CSSOM`: así como el DOM para el HTML, EL CSSOM es una representación de objetos de nuestros estilos en CSS.

`Render Tree`: es la unión entre el DOM y el CSSOM para renderizar todo el código de nuestra página web.

>Pasos que sigue el navegador para construir las páginas web:
1. Procesa el **HTML** para construir el **DOM**.
2. Procesa el **CSS** para construir el **CSSOM**.
3. El DOM se une con el **CSSOM** para crear el **Render Tree**.
4. Se aplican los estilos **CSS** en el **Render Tree**.
5. Se `pintan` los nodos en la pantalla para que los usuarios vean el contenido de la página web.

![Notas](https://static.platzi.com/media/user_upload/80-1e1adc16-ba31-4627-9d68-7ad1125285ab.jpg)

### 5 tips para aprender CSS

![5 Tips](https://static.platzi.com/media/user_upload/Infografia-Frontend-Javascript-986d1fea-9f09-4b8e-be0d-6d9f69ac75b8.jpg)