# Página Área Salud 2026

Proyecto web desarrollado con Vue.js para la gestión y difusión de información institucional, eventos, cursos y publicaciones del área de salud.

## Carreras asociadas

Este sistema está orientado a las carreras de:
- Medicina
- Enfermería
- Nutricion

## Descripción

Esta aplicación permite mostrar información relevante, comunicados, eventos, cursos, publicaciones y videos institucionales. Incluye páginas públicas, componentes reutilizables y una arquitectura moderna orientada a la escalabilidad y mantenibilidad.

## Estructura del proyecto

- `/src` — Código fuente principal (componentes, vistas, servicios)
- `/public` — Imágenes y recursos estáticos
- `/styles` — Hojas de estilo globales

## Instalación

```bash
# Clona el repositorio
git clone <URL-del-repositorio>
cd 2026-Pagina_area_salud

# Instala las dependencias
npm install

# Copia y configura variables de entorno si es necesario
cp .env.copy .env


# Inicia el entorno de desarrollo
npm run serve



## Scripts principales

- `npm run serve` — Inicia el servidor en modo desarrollo
- `npm run build` — Compila la aplicación para producción
- `npm run lint` — Ejecuta el linter

## Variables de entorno

Ajusta las variables en `.env` según tu entorno.

## Dependencias clave

- `vue` — Framework principal
- `vue-router` — Ruteo
- `axios` — Cliente HTTP
- `vuex` — Estado global (si aplica)

## Ejemplo de uso

```bash
# Levantar entorno local
npm run serve
# Accede a http://localhost:8080
```

## Notas adicionales

- El proyecto sigue buenas prácticas de seguridad y performance.
- Para producción, revisa la configuración en `vue.config.js`.

---

Desarrollado por el equipo UTIC — 2026.
