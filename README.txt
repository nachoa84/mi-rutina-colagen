# Mi Rutina Colagen v14 PWA

Esta carpeta contiene la versión instalable como PWA.

Archivos que deben subirse juntos:
- index.html
- manifest.webmanifest
- sw.js
- carpeta icons

Cómo probar:
1. Subir toda la carpeta a Netlify o GitHub Pages.
2. Abrir el link desde el celular.
3. En iPhone: Safari > Compartir > Agregar a pantalla de inicio.
4. En Android: Chrome > Instalar app o Agregar a pantalla principal.
5. Entrar a la app instalada y activar notificaciones desde la configuración inicial.

Importante: esta versión mejora la instalación y la experiencia. Las notificaciones del celular siguen dependiendo del sistema operativo, navegador y permisos. Para avisos 100% automáticos con la app cerrada, el siguiente paso es backend + Web Push real.


NOVEDAD v16:
- En Inicio > Editar rutina se agregó "Crear rutina nueva" para borrar la rutina actual y empezar de cero.
- También se agregó "Probar notificación ahora" para verificar permisos sin esperar al horario.
- Para probar el aviso diario: crear rutina nueva, configurar horario 2-3 minutos adelante, activar Aviso diario y no tocar "Ya lo tomé".
