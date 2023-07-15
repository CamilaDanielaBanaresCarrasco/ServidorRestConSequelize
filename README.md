# Servidor Rest con Sequelize

Este repositorio contiene un servidor REST básico desarrollado utilizando Sequelize. Este servidor proporciona una interfaz para realizar operaciones CRUD (Crear, Leer, Actualizar, Eliminar) en una base de datos utilizando el mapeador objeto-relacional Sequelize.

## Requisitos

- Node.js: Asegúrese de tener Node.js instalado en su sistema.
- npm: npm se instala automáticamente con Node.js. Si ya tiene Node.js instalado, asegúrese de tener npm actualizado.

## Instalación

Siga estos pasos para configurar y ejecutar el servidor:

1. Clonar el repositorio:  
git clone https://github.com/tu_usuario/ServidorRestConSequelize.git
2. Navegar al directorio del proyecto:
cd ServidorRestConSequelize
3. Instalar las dependencias:
npm install
4. Configurar la base de datos:
- Abra el archivo `config/config.js` y actualice la configuración de la base de datos según sus necesidades.
- Asegúrese de tener una base de datos creada y accesible.

5. Ejecutar las migraciones de la base de datos:
6. Iniciar el servidor:
7. El servidor ahora está en ejecución y listo para recibir solicitudes.

## Uso

El servidor REST proporciona puntos finales para realizar operaciones CRUD en la base de datos utilizando Sequelize. A continuación se muestra una breve descripción de los puntos finales disponibles:

- **GET /api/nombre_entidad**: Obtiene todos los registros de la entidad especificada.
- **GET /api/nombre_entidad/:id**: Obtiene un registro específico de la entidad según su ID.
- **POST /api/nombre_entidad**: Crea un nuevo registro en la entidad.
- **PUT /api/nombre_entidad/:id**: Actualiza un registro existente de la entidad según su ID.
- **DELETE /api/nombre_entidad/:id**: Elimina un registro de la entidad según su ID.

Reemplace `nombre_entidad` con el nombre de la entidad específica en su caso.

Para utilizar estos puntos finales, realice solicitudes HTTP correspondientes utilizando su cliente REST favorito (por ejemplo, Postman).

## Actualización de cambios

Si hay cambios en el repositorio y desea actualizar su copia local, siga estos pasos:

1. Asegúrese de estar en el directorio raíz del proyecto.

2. Obtenga los últimos cambios del repositorio remoto:
git pull origin main

3. Actualice las dependencias:
npm update

4. Reinicie el servidor si es necesario.

Con estos pasos, su copia local estará actualizada con los últimos cambios del repositorio.

¡Disfrute utilizando el servidor REST básico con Sequelize! Si tiene alguna pregunta o encuentra algún problema, no dude en crear un problema en el repositorio.
