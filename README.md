# Portafolio de Valeria

Portafolio web personal, responsivo y con tema oscuro azul. Está hecho solo con **HTML semántico** y **Tailwind CSS**, sin JavaScript.

## Secciones

- **Inicio:** presentación y botones a proyectos y CV(Aún sin enlazar).
- **Habilidades:** barras de progreso con las tecnologías que uso.
- **Proyectos:** tarjetas que enlazan a cada repositorio de GitHub.
- **Formación:** Estudios y certificaciones.
- **Contacto:** correo, GitHub y LinkedIn.

En escritorio el menú es una barra lateral flotante. En celular pasa a una barra inferior.

## Tecnologías

- HTML5 semántico
- [Tailwind CSS](https://tailwindcss.com/) v3 (CLI)
- Node.js y npm, solo para generar el CSS

## Estructura del proyecto

```
portafolio/
├── index.html
├── tailwind.config.js
├── package.json
├── README.md
└── css/
    ├── input.css
    └── styles.css
```

| Archivo | Para qué sirve |
| --- | --- |
| `index.html` | La página del portafolio. |
| `css/input.css` | Punto de partida de Tailwind (las tres directivas `@tailwind`). |
| `css/styles.css` | CSS generado por Tailwind. No se edita a mano. |
| `tailwind.config.js` | Indica en qué archivos buscar las clases usadas. |
| `package.json` | Dependencias y comandos del proyecto. |

## Cómo usarlo

### Solo ver la página

Abre `index.html` en el navegador. El CSS ya está generado en `css/styles.css`.

## Proyectos enlazados

| Proyecto | Repositorio |
| --- | --- |
| Rueda Libre | [valeryco/Rueda-Libre](https://github.com/valeryco/Rueda-Libre) |
| Hide Meal | [Felipe022911/Proyect](https://github.com/Felipe022911/Proyect) |
| IA | [valeryco/IA](https://github.com/valeryco/IA) |
| Algoritmia | [valeryco/Algoritmia](https://github.com/valeryco/Algoritmia) |
