# CRUD

El desarrollo de aplicaciones web es una tarea compleja que implica manejar datos de manera eficiente y confiable. Uno de los conceptos fundamentales en el desarrollo de aplicaciones es el CRUD, que consiste en las operaciones básicas de Crear, Leer, Actualizar y Eliminar datos en una base de datos.

![image](https://github.com/PFLC/610-crud-basicos-MariViz/assets/114043037/3a3fdeb0-2785-44f7-9a54-26201c56df7c)


## PHP: Crear (Create)

La operación de creación en el CRUD se refiere a la capacidad de agregar nuevos datos a una base de datos. En PHP, esto se puede lograr utilizando una combinación de HTML y PHP para crear un formulario de entrada de datos y procesar esa información para insertarla en la base de datos.

Primero, debemos diseñar un formulario HTML con campos correspondientes a los datos que deseamos capturar. Luego, mediante PHP, podemos obtener los valores ingresados en el formulario y ejecutar una consulta SQL para insertar esos datos en la base de datos.

## PHP: Leer (Read)

La operación de lectura en el CRUD implica recuperar datos almacenados en una base de datos y mostrarlos en una interfaz de usuario. En PHP, podemos utilizar consultas SQL SELECT para recuperar los datos deseados de la base de datos.

Luego, podemos procesar los resultados de la consulta y mostrarlos en la interfaz de usuario utilizando HTML y PHP. Esto nos permite mostrar información específica de la base de datos a los usuarios de nuestra aplicación web.

## PHP: Actualizar (Update)

La operación de actualización en el CRUD se utiliza para modificar los datos existentes en la base de datos. En PHP, podemos utilizar un formulario similar al utilizado en la operación de creación para mostrar los datos actuales y permitir al usuario realizar modificaciones.

Al enviar el formulario, podemos procesar los datos actualizados utilizando PHP y ejecutar una consulta SQL UPDATE para aplicar los cambios en la base de datos. Esto nos brinda la capacidad de mantener los datos actualizados y reflejar los cambios realizados por los usuarios.

## PHP: Eliminar (Delete)

La operación de eliminación en el CRUD se utiliza para eliminar datos de la base de datos. En PHP, podemos utilizar un enlace o un botón que, al ser activado por el usuario, ejecuta una consulta SQL DELETE para eliminar los datos correspondientes en la base de datos.

Es importante tener cuidado al implementar esta funcionalidad y considerar la seguridad de la aplicación, ya que la eliminación de datos puede ser irreversible y potencialmente causar problemas si no se gestiona adecuadamente.

# Aplicación CRUD de PHP

Este repositorio contiene una aplicación PHP CRUD (Create, Read, Update, Delete) simple. Es una demostración básica de cómo integrar PHP con una base de datos MySQL para gestionar datos de usuarios. La aplicación permite a los usuarios agregar, ver, editar y eliminar información de usuario.

## Tecnologías Utilizadas

- **PHP:** Lenguaje de script del lado del servidor utilizado para el desarrollo web.
- **MySQL:** Sistema de gestión de base de datos utilizado para almacenar datos de usuario.
- **HTML & CSS:** Utilizados para estructurar y dar estilo a las páginas web.
- **Tailwind CSS:** Un framework de CSS utilitario para el desarrollo rápido de interfaces de usuario.

## Páginas y Funcionalidades

### 1. Página de Inicio (`display.php`)

![Página de Inicio](images/display.png)

- **Funcionalidad:** Muestra todos los usuarios de la base de datos en un formato de tabla.
- **Características:** 
  - Ver todos los usuarios.
  - Enlaces de navegación para agregar, editar o eliminar información de usuario.

### 2. Agregar Usuario (`user.php`)

![Agregar Usuario](images/add.png)

- **Funcionalidad:** Permite agregar un nuevo usuario a la base de datos.
- **Características:** 
  - Formulario para ingresar detalles del usuario (nombre, correo electrónico, teléfono móvil, contraseña).
  - Validación de datos y envío a la base de datos.

### 3. Editar Usuario (`edit.php`)

![Editar Usuario](images/edit.png)

- **Funcionalidad:** Permite editar detalles de usuarios existentes.
- **Características:** 
  - Formulario prellenado con la información actual del usuario.
  - Actualización de detalles del usuario en la base de datos.

### 4. Eliminar Usuario (`delete.php`)

- **Funcionalidad:** Facilita la eliminación de un usuario de la base de datos.
- **Características:** 
  - Eliminación de información de usuario basada en el ID de usuario.

## Conexión a la Base de Datos (`connect.php`)

- **Propósito:** Establece una conexión con la base de datos MySQL.
- **Credenciales:** Utiliza nombre de host, nombre de usuario, contraseña y nombre de la base de datos para la conexión.

## Cómo Ejecutar

1. Clona el repositorio en tu máquina local.
2. Configura un entorno PHP y MySQL (como XAMPP).
3. Crea la base de datos usando phpmyadmin.
4. Ejecuta la aplicación en un servidor local.

## Nota de Seguridad

Esta aplicación es una demostración básica y no implementa medidas avanzadas de seguridad. Es recomendable utilizar declaraciones preparadas (prepared statements) u ORM para las interacciones con la base de datos para prevenir ataques de inyección SQL.

# Conclusión

La implementación del CRUD en PHP junto con bases de datos nos brinda una poderosa herramienta para gestionar datos en aplicaciones web. Mediante la combinación de HTML y PHP, podemos crear formularios de entrada, mostrar datos, actualizar registros y eliminar información de manera eficiente y segura.

Es fundamental comprender y aplicar adecuadamente estas operaciones básicas para desarrollar aplicaciones web robustas y funcionales. Al dominar el CRUD en PHP, los desarrolladores pueden construir aplicaciones web dinámicas que interactúan con bases de datos de manera efectiva, mejorando así la experiencia del usuario y la eficiencia en el manejo de datos.

![image](https://github.com/PFLC/610-crud-basicos-MariViz/assets/114043037/22b71d6b-c506-4075-a279-aa5a2b9c9618)

---

Siéntete libre de contribuir a este proyecto o sugerir mejoras. Para cualquier consulta o problema, por favor abre un issue en este repositorio.

