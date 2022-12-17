# Coder Desarrollo Web 36415
> Coder House Curso de Desarrollo Web Carrera Full Stack

---

### Estructura del proyecto

```
├───assets
│   ├───img
│   │   ├───extra
│   │   ├───favicon
│   │   └───perfil
│   └───logos
├───css
├───doc
└───pages
```

IR A  [**DECOD SITE**](https://dacerb.github.io/full-stack-coderhouse/)
---

[**Consigna**](./doc/preEntrega3/coder-preentrega.pdf)

[**PDF W**ireFame](./doc/preEntrega1/WireFramePreEntrega1.pdf)

[**Figma**](https://www.figma.com/file/eTDgxn02dVJJvCabktpbwO/WireFrame-Prototipo?node-id=50%3A7)

![Alt text](./doc/preEntrega1/Group%2039.svg)



---
# Instalación
>

>Instalamos node-sass y nodemon en modo -D develop.
````
$ npm install -D node-sass nodemon
````

> Al package.json agreamos la definicion del script que se 
inicia con watch.css que inicia al build-csss
````
"scripts": {
    "build-css": "node-sass --include-path scss scss/main.scss css/styles.css",
    "watch-css": "nodemon -e scss -x \"npm run build-css\""
  },
````

# Ejecucion del builder de SCSS
> Iniciar watch para compilar scss -> css
 
````
npm run watch-css
````

[**Link netlify**](https://sparkly-lolly-2a9ba6.netlify.app/)
