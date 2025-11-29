# API REST con Node.js y Express

## Descripción

Este proyecto consiste en una **API REST** creada con **Node.js** y **Express.js**. La API permite realizar operaciones CRUD (Crear, Leer, Actualizar y Eliminar) sobre una lista de usuarios almacenada en memoria.

---

## Instrucciones

Asegurarse de tener instalados: Node y npm. Para verificar esto, se utilizan dos comandos en nuestra terminal:

- **Node**: Node --version

- **npm**: npm -v

Una vez hecho esto, ingresamos a nuestro **VS Code** en donde iremos a la sección de **Extensiones**, en donde vamos a utilizar una extensión llamada **Thunder Client**, esta extensión permite peticiones **HTTP** dentro de VS Code.

Una vez hecho esto, creamos una carpeta en donde vamos a comenzar el proyecto. En la terminal de dicho proyecto, se van a escribir los siguientes comandos:

- **npm init -y**: Para inicializar el proyecto.
- **npm install --save-dev nodemon**: Para la instalación de las dependencias.

Después de esto, se configura un script en **package.json** para que el proyecto pueda correr automáticamente con `nodemon`.

## Ejecución del Proyecto

Para ejecutar el proyecto, usa el siguiente comando:

- **npm run dev**

El servidor se ejecutará en el puerto 3000. Se accede a la API utilizando las siguientes rutas:

- **GET /**: Devuelve un mensaje de bienvenida.

- **GET /usuarios**: Devuelve la lista completa de usuarios.

- **POST /usuarios**: Permite agregar un nuevo usuario enviando datos mediante JSON.

- **PUT /usuarios/:id**: Permite actualizar un usuario mediante JSON.

- **DELETE /usuarios/:id**: Permite eliminar un usuario.
