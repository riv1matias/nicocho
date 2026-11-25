# nicocho

Web de **Custom Sal de Asador** (distribuidor Nicolás): landing para Instagram + tienda online.

Template / prototipo estático (HTML + CSS + JS, sin dependencias). Abrí `index.html` en el navegador o publicalo con GitHub Pages.

## Qué incluye

- Landing con la estética del catálogo (azul noche, dorado, un color por categoría).
- Tienda con los 114 productos y 12 categorías del catálogo de noviembre 2026: búsqueda, filtros, orden, ofertas.
- Carrito con aviso de la promo "10 Sales Gourmet → 1 de regalo".
- Checkout que genera un código de pedido (CS-xxxx) y arma el mensaje para enviarlo por WhatsApp.
- Cuentas de cliente: registro, login, datos de entrega, historial y "Repetir pedido".
- Seguimiento de pedido por código (Recibido → Confirmado → Preparando → En camino → Entregado).
- Panel del distribuidor (`#panel`) para cambiar estados y avisar al cliente por WhatsApp.
- Responsive con barra de navegación inferior en celular.

## Importante

Es una demo: cuentas y pedidos se guardan en `localStorage` del navegador de cada usuario. Para producción hace falta un backend (por ejemplo Firebase Auth + Firestore) o migrar el diseño a una plataforma de e-commerce, más un medio de pago.

Precios en ARS vigentes al 03/11/2026 según el catálogo; los datos de productos están embebidos en `index.html` (`const DATA=`). Las fotos de `img/` salen del PDF del catálogo (baja resolución): conviene reemplazarlas por las originales.
