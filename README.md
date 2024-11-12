
# To-Do List

Este proyecto es una aplicación de lista de tareas (To-Do List) desarrollada con **React**, **Tailwind CSS** y **Vite**. Permite a los usuarios crear, editar, marcar como completadas y eliminar tareas. Es una aplicación ideal para aprender a usar React con Tailwind y Vite en un proyecto sencillo y práctico.

## Tabla de Contenidos

- [Características](#características)
- [Requisitos](#requisitos)
- [Instalación](#instalación)
- [Uso](#uso)
- [Estructura del Proyecto](#estructura-del-proyecto)
- [Tecnologías](#tecnologías)
- [Autor](#autor)
- [Licencia](#licencia)

## Características

- Añadir, editar y eliminar tareas.
- Marcar tareas como completadas.
- Interfaz de usuario responsiva y estilizada con Tailwind CSS.
- Almacenamiento de tareas en el almacenamiento local del navegador.

## Requisitos

Asegúrate de tener las siguientes herramientas instaladas en tu sistema:

- [Node.js](https://nodejs.org/) (versión 14 o superior)
- [NPM](https://www.npmjs.com/) o [Yarn](https://yarnpkg.com/)

## Instalación

Para instalar y ejecutar este proyecto en tu entorno local:

1. Clona este repositorio:

   ```bash
   git clone https://github.com/neilsimez/todo-list.git
   cd todo-list
   ```

2. Instala las dependencias:

   ```bash
   npm install
   ```

   o si prefieres Yarn:

   ```bash
   yarn install
   ```

3. Ejecuta el servidor de desarrollo:

   ```bash
   npm run dev
   ```

   o con Yarn:

   ```bash
   yarn dev
   ```

4. Abre el navegador y accede a `http://localhost:3000`.

## Uso

1. En la interfaz principal, puedes:
   - **Añadir** una nueva tarea escribiendo en el campo de entrada y pulsando Enter.
   - **Editar** el texto de una tarea.
   - **Eliminar** una tarea específica.
   - **Marcar** una tarea como completada o pendiente.

2. Las tareas se almacenan en el almacenamiento local, por lo que estarán disponibles incluso después de recargar la página o cerrar el navegador.

## Estructura del Proyecto

```
├── public/                     # Archivos estáticos
├── src/
│   ├── components/             # Componentes de React
│   │   ├── TaskItem.jsx        # Componente de una tarea individual
│   │   └── TaskList.jsx        # Componente lista de tareas
│   ├── App.jsx                 # Componente principal de la aplicación
│   ├── index.jsx               # Punto de entrada de React
│   └── styles.css              # Archivo de estilos de Tailwind
├── .gitignore
├── package.json
├── README.md                   # Documentación del proyecto
└── vite.config.js              # Configuración de Vite
```

## Tecnologías

- **[React](https://reactjs.org/):** Librería de JavaScript para crear interfaces de usuario.
- **[Vite](https://vitejs.dev/):** Herramienta de desarrollo rápida y ligera para aplicaciones modernas de frontend.
- **[Tailwind CSS](https://tailwindcss.com/):** Framework CSS para un diseño estilizado y responsivo.

## Autor

Creado por **Neilsimez**. Puedes contactarme en [tu-email@dominio.com] o en mis redes sociales.

## Licencia

Este proyecto está bajo la licencia MIT. Puedes ver más detalles en el archivo [LICENSE](./LICENSE).
