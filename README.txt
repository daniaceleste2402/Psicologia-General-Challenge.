Psicología General Challenge - prototipo de juego en tiempo real

Requisitos: Node.js 18 o superior.

1. Abre una terminal en esta carpeta.
2. Ejecuta: npm install
3. Ejecuta: npm start
4. En la computadora docente abre http://localhost:3000/host
5. Para que los celulares entren, computadora y teléfonos deben estar en la misma red Wi-Fi. Abre en la computadora la dirección IP local (ej. http://192.168.1.20:3000/host) en lugar de localhost; el QR utilizará esa dirección.
6. Para acceso desde cualquier red, publica este servidor Node.js en un alojamiento con WebSockets y configura la variable PUBLIC_URL con la dirección HTTPS pública.

Importante: El servidor conserva los datos solo en memoria; al reiniciarlo se pierden las partidas. No usar nombres completos de menores. No incluye autenticación docente; úsalo en red de confianza o añade autenticación antes de publicarlo.
