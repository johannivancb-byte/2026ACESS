# Semana de Nivelación · IENC Sede San Nicolás

Página web del horario de nivelación (10 al 17 de noviembre de 2026).

## Archivos

- `index.html`: la página completa (horarios + sección cifrada).
- `logo.png`: logo institucional.

## Cómo publicar en GitHub Pages

1. Sube `index.html` y `logo.png` a la raíz del repositorio (o a una carpeta).
2. En el repositorio: **Settings → Pages → Branch: main → Save**.
3. Espera 1 o 2 minutos y abre el enlace que muestra GitHub.

## Secciones

| Pestaña | Para quién | Qué muestra |
|---|---|---|
| 📚 Curso | Estudiantes y acudientes | Salón base y "¿La debes? ➜ Salón X" por bloque |
| 👩‍🏫 Docente | Docentes | Rol, salón y acción de cada bloque |
| 🎓 Grado | Coordinación | Vista consolidada del grado |
| 🏫 Salón | Coordinación | Quién ocupa cada aula en cada bloque |
| ⏱️ Ahora | Coordinación | Qué pasa en todo el colegio en este momento |
| 🔒 Docentes | Solo docentes (contraseña) | Buscar estudiante, listas por salón con notas, seguimiento de riesgo |

## Seguridad

- La información de estudiantes (nombres, asignaturas y notas) está **cifrada** dentro de `index.html`. Sin la contraseña no se puede leer, ni siquiera revisando el código.
- La contraseña **no está en este repositorio**. Compártela solo con docentes, por mensaje privado.
- La página tiene la etiqueta `noindex`, para que los buscadores no la muestren.
- **Al terminar la semana, borra `index.html` del repositorio** o desactiva GitHub Pages.

## Enlace a las planillas en Drive (opcional)

En `index.html`, busca la línea:

```js
const DRIVE_URL="";
```

Pega entre las comillas el enlace de la carpeta **03 Planillas ACES** de Google Drive. Aparecerá un botón "📂 Planillas PDF" dentro de la sección de docentes.
