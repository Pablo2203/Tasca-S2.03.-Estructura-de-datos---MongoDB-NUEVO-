# 📘 Ejercicios de Modelado de Bases de Datos

Este repositorio contiene los ejercicios de modelado de bases de datos realizados en base a varios escenarios y requerimientos prácticos. Los ejercicios abordan diferentes niveles de dificultad, desde la gestión de datos de una óptica hasta la creación de un modelo simplificado de una plataforma como YouTube.

---

## 📄 Descripción - Enunciado del Ejercicio

Este proyecto está dividido en tres niveles, con diferentes ejercicios:

### **Nivel 1**
1. **Óptica "Cul d'Ampolla"**  
    Se requiere el diseño de una base de datos que pueda gestionar la información de clientes, proveedores, empleados, ventas y gafas desde dos puntos de vista diferentes:
    - Desde la perspectiva del cliente.
    - Desde la perspectiva de las gafas.

2. **Diseño de Base de Datos Corporativa**  
    Este nivel introduce el modelado requerido para manejar una óptica completa, que incluye detalles de los productos (gafas), la relación con proveedores y empleados, además del registro de ventas.

---

### **Nivel 2**
1. **Pedido de Comida a Domicilio**  
    Diseño de una base de datos que permita gestionar un sistema de pedidos de comida online. La base de datos debe gestionar:
    - Información de los clientes.
    - Relación de productos (pizza, hamburguesas, bebidas).
    - Gestión de pedidos y entrega (incluyendo empleados y repartidores).
    - Detalle de las categorías de productos, que pueden variar con el tiempo.

---

### **Nivel 3**
1. **Modelo Sencillo de YouTube**  
    Diseño de una base de datos que permita gestionar usuarios, videos, canales, comentarios y playlists. Los requisitos incluyen:
    - Almacenamiento de información de usuarios y sus relaciones (likes, dislikes, suscripciones).
    - Gestión de los videos y su metadata (etiquetas, estados, reproducciones, etc.).
    - Creación y personalización de canales y playlists por los usuarios.

---

## 💻 Tecnologías Utilizadas

- **Lenguaje de consulta:** SQL y modelado de bases de datos relacionales.
- **Base de datos utilizadas:** Adaptaciones para sistemas como MySQL, PostgreSQL y MongoDB, según el ejercicio.
- **Herramientas de diseño:** Diagramas E-R creados con herramientas como **dbdiagram.io**, **draw.io**, o equivalentes.
- Otras tecnologías que podrían aplicarse en ejemplos reales: **Node.js**, **JavaScript**, **HTML/CSS** (para interfaces de usuario).

---

## 📋 Requisitos

Antes de clonar este proyecto, asegúrate de tener las siguientes herramientas instaladas:

- **Un servidor de base de datos** compatible (como MySQL o PostgreSQL).
- [Node.js y npm](https://nodejs.org/) (si tienes aplicaciones adicionales de backend).
- [MongoDB](https://www.mongodb.com/es) (si trabajas con modelos NoSQL).
- Editor de código fuente (como **IntelliJ IDEA** o **VSCode**).

---

## 🛠️ Instalación

Sigue estos pasos para configurar el proyecto en tu entorno local:

1. Clona este repositorio en tu máquina local:
   ```bash
   git clone https://github.com/tu-usuario/tu-repositorio.git
   cd tu-repositorio
   ```

2. Si trabajas con SQL:  
   Configura y crea la base de datos según el `schema.sql` proporcionado en cada ejercicio.

3. Si trabajas con MongoDB:  
   Inserta los documentos iniciales desde los archivos JSON proporcionados con:
   ```bash
   mongoimport --db tu_base_de_datos --collection tu_coleccion --file datos.json
   ```

4. Consulta los archivos **README internos de cada ejercicio** para conocer configuraciones adicionales.

---

## ▶️ Ejecución

1. Inicia tu servicio de base de datos (MySQL/PostgreSQL/MongoDB según corresponda).
2. Ejecuta las consultas en tu gestor de base de datos preferido:
   - MySQL: Usa herramientas como **MySQL Workbench**.
   - PostgreSQL: Usa **pgAdmin** o la CLI de `psql`.
   - MongoDB: Usa **MongoDB Compass** o la CLI de `mongo`.
3. Sigue los pasos proporcionados en los **README específicos** de cada nivel o ejercicio.

---

## 🌐 Despliegue

1. Para producción, asegúrate de que el servidor de base de datos esté configurado con los siguientes criterios:
   - **Seguridad:** Credenciales seguras y restricciones de acceso.
   - **Backups automatizados** de las bases de datos.
2. Si el proyecto incluye API/web, puedes desplegarlo usando servicios como **Docker**, **Heroku**, o **AWS**.
3. Consulta la documentación correspondiente para la herramienta elegida.

---

## 🤝 Contribuciones

¡Las contribuciones son bienvenidas! Si deseas colaborar:

1. Crea un **fork** de este repositorio.
2. Crea una rama con los cambios que quieres realizar:
   ```bash
   git checkout -b nueva-feature
   ```
3. Realiza tus cambios y haz un commit:
   ```bash
   git commit -m "Añadida nueva funcionalidad"
   ```
4. Envía un **pull request** para revisar los cambios.

---

Si tienes preguntas o sugerencias, por favor abre un **issue** en el repositorio o contáctame por correo.

### ¡Gracias por tu interés y colaboración! 😊
