# Proyecto Web Ejemplo

Repositorio público de demostración con un proyecto web simple en HTML y CSS. Contiene una versión estable en `main` y una rama de mejora de estilo en `feature-mejora-estilo`.

## Descripción

Este proyecto muestra un sitio web estático básico con una estructura HTML semántica, estilos CSS modernos y un diseño responsive. Su propósito es practicar el flujo de trabajo de Git y GitHub.

## Contenido del repositorio

- `index.html`: Página principal del proyecto.
- `styles.css`: Hoja de estilos con diseño visual moderno.
- `README.md`: Documentación del proyecto.

## Cómo clonar y ejecutar el proyecto en local

1. Abre una terminal.
2. Clona el repositorio:

```bash
git clone https://github.com/brayansantiagocuta-eng/Proyecto-Web-Ejemplo.git
cd Proyecto-Web-Ejemplo
```

3. Verifica las ramas disponibles:

```bash
git branch -a
```

4. Abre `index.html` en tu navegador para ver el sitio.

> También puedes usar un servidor local simple, por ejemplo con Python:
>
> ```bash
> python -m http.server 8000
> ```
>
> Luego abrimos `http://localhost:8000` en el navegador.

## Ramas del proyecto

- `main`: Rama principal con la versión estable del proyecto y la integración final de las mejoras.
- `feature-mejora-estilo`: Rama de trabajo donde se aplicaron cambios visuales y mejoras de estilo en CSS y HTML.

## Flujo de trabajo

1. Se creó el proyecto inicial y se subió a GitHub.
2. Se creó la rama `feature-mejora-estilo` para mejorar el estilo y la presentación.
3. Se simuló un cambio en `main` que generó un conflicto en `styles.css`.
4. Se resolvió el conflicto y se fusionó el trabajo en `main`.

## Estado actual

El código fuente está completo, la documentación contiene instrucciones de clonación y ejecución, y la rama de características está integrada en `main`.
