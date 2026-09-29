
# Taller #2 — Astro + Supabase + Cloudflare

## 🎯 Objetivo

Construir una aplicación web utilizando **Astro** que permita:

- Mostrar una lista pública de películas.
- Buscar y paginar las películas.
- Autenticar usuarios mediante Supabase.
- Crear, editar y eliminar películas.
- Proteger los datos mediante Row Level Security (RLS).
- Utilizar View Transitions para mejorar la navegación.
- Desplegar el proyecto en Cloudflare.
- Documentar el proyecto en GitHub.

---

# 📋 Entregables

El taller tiene los siguientes entregables:

1. Repositorio público en GitHub.
2. Proyecto desarrollado con Astro.
3. Archivo `.env.example`.
4. Archivo `README.md`.
5. Aplicación desplegada públicamente en Cloudflare.
6. Demostración en clase.
7. Responder la pregunta individual del taller.

---

# 🛠️ Tecnologías principales

| Tecnología | Uso                                     |
| ----------- | --------------------------------------- |
| Astro       | Framework principal                     |
| Vue         | Opcional, para componentes interactivos |
| Supabase    | Base de datos + autenticación          |
| PostgreSQL  | Base de datos utilizada por Supabase    |
| Cloudflare  | Despliegue                              |
| GitHub      | Repositorio                             |

> Vue NO es obligatorio. Astro es la tecnología principal del taller.
> Podemos utilizar Vue para componentes interactivos si lo necesitamos.

---

# 🏗️ ¿Qué debemos construir?

La aplicación estará basada en una temática de películas.

La idea general será tener:

```text
Usuario
   │
   ├── Página pública de películas
   │       ├── Buscar
   │       └── Paginar
   │
   ├── Login
   │
   └── Dashboard
           ├── Crear película
           ├── Editar película
           └── Eliminar película
```
