# StudyMate — práctica oral de Inglés I

Sitio estático para practicar la entrevista del proyecto StudyMate. No requiere dependencias ni proceso de compilación.

## Flujo de práctica

- Una vuelta: muestra el guion en pantalla.
- Dos vueltas: muestra el guion en la primera; lo oculta en la segunda.
- Bucle infinito: muestra el guion solo en la primera vuelta y continúa de memoria en las siguientes.
- En las vueltas de memoria, se puede revelar únicamente la intervención actual.

## Archivos

- `index.html`: aplicación de práctica.
- `audios/integrador_job_interview.mp3`: audio del reproductor.

Mantené el MP3 dentro de `audios/`; el HTML usa esa ruta relativa.

## Ejecutar localmente

Abrí `index.html` en un navegador. Si el navegador bloquea audio al abrir archivos locales, serví esta carpeta con cualquier servidor estático.

## Publicar en Vercel

Importá el repositorio en Vercel y usá la raíz del repositorio como directorio del proyecto. No hay comando de build ni carpeta de salida adicional: es un sitio HTML estático.
