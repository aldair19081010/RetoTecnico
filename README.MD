# Reto Técnico: Lista de 10 Personas Aleatorias

Este proyecto es una pequeña aplicación web que muestra una lista de 10 personas generadas aleatoriamente usando la API pública randomuser.me. La idea es demostrar cómo separar el back-end y el front-end, usando tecnologías sencillas y fáciles de mantener.

---

## ¿Qué hace este proyecto?

- El back-end (PHP puro) expone una API RESTful (`api.php`) que devuelve 10 personas en formato JSON.
- El front-end (`index.html`) es una SPA que consume esa API y muestra los datos en una tabla.
- Puedes filtrar por nombre y género, y recargar la lista con un botón.
- El diseño es minimalista, responsivo y fácil de leer.

---

## ¿Cómo lo uso?

1. Descarga o clona este repositorio en tu carpeta de tu servidor local (por ejemplo, `htdocs` de XAMPP).
2. Asegúrate de tener PHP funcionando (no necesitas base de datos ni frameworks).
3. Abre tu navegador y entra a:  
   `http://localhost/RetoTecnico/index.html`

¡Listo! Ya puedes ver la lista, filtrar y recargar tantas veces como quieras.

---

## ¿Qué tecnologías usé y por qué?

- **PHP puro** para el back-end: rápido de implementar, fácil de probar en cualquier entorno local y sin dependencias extra.
- **HTML5, CSS3 y JavaScript vanilla** para el front-end: así el código es claro, portable y fácil de entender para cualquier desarrollador.
- **randomuser.me** como fuente de datos: es una API pública, ideal para pruebas y ejemplos.

---

## ¿Qué puedes mejorar o agregar?

- Paginación para ver más personas.
- Filtros por país, edad, etc.
- Exportar la tabla a CSV o PDF.
- Mostrar detalles ampliados al hacer clic en una persona.
- Migrar el back-end a un framework si el proyecto crece.

---

## ¿Quién hizo esto?

Desarrollado por [Tu Nombre].

Si tienes dudas, sugerencias o quieres mejorar el proyecto, ¡adelante! El código es tuyo para experimentar.

---

## Recursos útiles

- [randomuser.me](https://randomuser.me/documentation)
- [PHP](https://www.php.net/manual/es/)
- [HTML5](https://developer.mozilla.org/es/docs/Web/Guide/HTML/HTML5)
- [CSS3](https://developer.mozilla.org/es/docs/Web/CSS)

¡Gracias por revisar el proyecto!

# RetoTecnico
