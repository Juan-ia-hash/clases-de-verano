# Clases de Verano

## Publicar en Vercel

Importa este repositorio y deja Root Directory en la raíz (`./`). El archivo `vercel.json` configura la página estática, sin instalación ni compilación, y publica `dist`. No elijas `dist` como Root Directory. Al actualizar el repositorio, Vercel debe crear un nuevo despliegue si la integración de GitHub está activa.

Demo estática sin instalaciones ni base de datos. Abre `dist/index.html` con tu navegador para usarla localmente. Los estilos y las ilustraciones funcionan sin conexión; la fuente Nunito utiliza Google Fonts y tiene fuentes locales de respaldo.

## Cambios

- Nombre, programas, talleres, teléfono y dirección: `dist/config.js`.
- Horario visible, preguntas frecuentes y textos generales: `dist/index.html`.
- Colores, tamaños y adaptación móvil: `dist/styles.css`.
- Mascota y dibujos SVG, exploración de talleres y formulario: `dist/app.js`.

El formulario solo prepara el mensaje y abre WhatsApp; la persona debe revisarlo y enviarlo. No guarda datos ni confirma inscripciones. El mapa es ilustrativo y el enlace busca la dirección real sin coordenadas inventadas.

Las ilustraciones originales son SVG para mantenerlas ligeras y animables. No se utilizan fotografías ni testimonios ficticios. La opción de pausa está en el pie y se respeta la preferencia de movimiento reducido del dispositivo.
