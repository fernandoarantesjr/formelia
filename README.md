# Formelia — sitio web

Tienda de Formelia (impresión 3D personalizada, Encarnación · Paraguay).
Sitio estático: `index.html` + video de la página "Nosotras". Sin build.

## Deploy en Vercel
Importar el repositorio en Vercel → Framework: **Other** → sin comando de build → Deploy.

## Cambiar la colección del momento
En `index.html`, buscar `COLECCION` y cambiar título, texto, color y la lista de `productos`.
`activa: false` la oculta.

## Productos
Lista `P` en `index.html`: nombre, línea, precio, descripción.
WhatsApp de pedidos: variable `WPP`.

## Modelos 3D
Cada producto puede tener `model: 'models/archivo.glb'` (modelo real) e `img: 'images/foto.jpg'` (foto del card).
En el GLB, las piezas cuyo nombre empieza con `accent` toman el color elegido por el cliente.
`price: null` muestra "A consultar".
