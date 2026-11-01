# blackjack-21-deploy

Repositorio **solo de despliegue**. No edites nada aquí: lo genera y lo sube automáticamente el repositorio de código (`blackjack-21-src`) en cada push a `main`.

| Rama | Contenido | Quién lo sirve |
|------|-----------|----------------|
| `main` | Web estática + funciones `api/` ya compiladas | **Vercel** (Production Branch = `main`) |
| `pages` | Solo la web estática | **GitHub Pages** (Source = rama `pages`, carpeta `/`) |

El código fuente legible vive en el repositorio privado de código. Aquí solo hay salida compilada y ofuscada.
