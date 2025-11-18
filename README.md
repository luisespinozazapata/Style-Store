# Style Store

Tienda online SPA de ropa construida con React.js — proyecto académico de Cibertec. Diseñada para una experiencia rápida y moderna, incluye búsqueda, catálogo con filtros, detalle de producto, carrito interactivo y un flujo de checkout sencillo.

---

## Características principales

- Búsqueda de productos por nombre con resultados instantáneos.
- Catálogo con filtros por categoría y paginación (si aplica).
- Página de detalle con carrusel de imágenes, selección de talla y cantidades.
- Carrito de compras dinámico (añadir/eliminar/actualizar cantidades).
- Checkout con formulario de envío y opciones de pago (simulado).
- Diseño responsive para móviles y escritorio.
- UI moderna con CSS (posible uso de preprocesadores o librerías CSS).
  
---

## Tecnologías

- React.js (Create React App / Vite)
- React Router
- Context API / Redux (según implementación)
- CSS / SASS para estilos
- Opcional: librerías de componentes (Material UI, Bootstrap) o carrusel (Swiper)
- HTML / JavaScript.
  
---

## Capturas

Inicio  
![Inicio](https://github.com/user-attachments/assets/1f763d8c-46b7-4924-a052-221aa8f0a8ef)

Catálogo de Mujeres  
![Catálogo de Mujeres](https://github.com/user-attachments/assets/ef67f6d9-3630-4d59-bbc8-9cf17753bfab)

Detalle de Producto  
![Detalle de Producto](https://github.com/user-attachments/assets/49a8c18d-64f9-44a2-9bc9-496a9874b024)

Carrito de compras  
![Carrito de compras](https://github.com/user-attachments/assets/6fd594ef-c710-4433-9534-e3b5cb47772c)

Checkout  
![Checkout](https://github.com/user-attachments/assets/a9d9910f-cfc3-4876-be23-df8c6af44500)

Busquedas  
![Busquedas](https://github.com/user-attachments/assets/f185b49c-c2ed-496e-8802-6635798ab224)

---

## Instalación rápida

1. Clona el repositorio:
```bash
git clone https://github.com/luisespinozazapata/Style-Store.git
cd Style-Store
```

2. Instala dependencias:
```bash
npm install
# o
yarn install
```

3. Ejecuta en modo desarrollo:
```bash
npm start
# o
yarn start
```

4. Abrir en el navegador:
- Visita http://localhost:3000 (o el puerto que indique la consola)

5. Construir para producción:
```bash
npm run build
# o
yarn build
```

---

## Estructura sugerida del proyecto

- /src
  - /components — componentes reutilizables (Header, Footer, ProductCard, Carousel)
  - /pages — páginas (Home, Catalog, ProductDetail, Cart, Checkout)
  - /context o /store — manejo de estado global (carrito, usuario)
  - /assets — imágenes y recursos estáticos
  - /utils — utilidades (formatos, helpers)
  - index.js / App.js

---

## Buenas prácticas y consejos

- Validar entradas del checkout y mostrar errores de forma clara.
- Guardar carrito en localStorage para persistencia entre sesiones.
- Manejar estados de carga y mensajes de error al obtener datos.
- Agregar tests unitarios para componentes críticos (carrito, checkout).
- Optimizar imágenes y usar lazy-loading en galerías.

---

## Cómo contribuir

1. Haz fork del repositorio.
2. Crea una rama con tu feature o fix:
```bash
git checkout -b feature/nombre-de-mi-feature
```
3. Haz commits claros y atómicos.
4. Abre un Pull Request con descripción del cambio y screenshots si corresponde.

---

## Contacto

- Autor: Luis Espinoza
- GitHub: https://github.com/luisespinozazapata
- Correo: I202224202@cibertec.edu.pe

¡Gracias por visitar Style Store! Si quieres, puedo preparar un README en inglés, añadir badges (build / license / cobertura) o generar un CHANGELOG y plantilla de contribución.
