📚 Curso de Bases de Datos MySQL
Repositorio dedicado al aprendizaje práctico de MySQL, desde los conceptos fundamentales de bases de datos relacionales hasta el desarrollo de proyectos completos orientados a escenarios reales.

🎯 Objetivos
Este repositorio tiene como finalidad:

Aprender los fundamentos de SQL.
Diseñar bases de datos relacionales.
Implementar restricciones de integridad.
Trabajar con consultas simples y avanzadas.
Desarrollar procedimientos almacenados y funciones.
Gestionar usuarios, roles y permisos.
Aplicar buenas prácticas en proyectos reales.
🛠️ Tecnologías
MySQL 8.0
MySQL Workbench
SQL (DDL, DML y DCL)
📂 Estructura del Repositorio
curso-bases-datos-mysql/
│
├── fundamentos/
├── consultas-basicas/
├── consultas-avanzadas/
├── restricciones/
├── procedimientos-almacenados/
├── funciones/
├── triggers/
├── gestion-usuarios-y-roles/
│
├── proyectos/
│   ├── autoescuela_db/
│   └── tienda_videojuegos/
│
└── README.md
📖 Contenidos
🔹 Fundamentos SQL
Creación de bases de datos
Creación de tablas
Tipos de datos
Claves primarias
Claves foráneas
🔹 Manipulación de Datos
INSERT
UPDATE
DELETE
SELECT
🔹 Consultas Avanzadas
WHERE
ORDER BY
GROUP BY
HAVING
JOIN
Subconsultas
🔹 Restricciones
PRIMARY KEY
FOREIGN KEY
UNIQUE
NOT NULL
CHECK
AUTO_INCREMENT
🔹 Programación en MySQL
Procedimientos almacenados
Funciones
Variables
Condicionales IF
Cursores
🔹 Administración
Usuarios
Roles
Privilegios
Seguridad
🚗 Proyecto: Autoescuela
Sistema de gestión para una autoescuela enfocado en el control de conductores, permisos y renovaciones de licencias.

Conceptos aplicados
Restricciones CHECK
Validación de datos
Procedimientos almacenados
Consultas parametrizadas
Integridad de datos
🎮 Proyecto: Tienda de Videojuegos
Base de datos relacional para la gestión de una tienda online de videojuegos.

Características principales
Gestión de clientes.
Catálogo de videojuegos.
Control de stock.
Registro de pedidos.
Gestión de detalles de compra.
Restricciones de integridad referencial.
Modelo Relacional
CLIENTES
    │
    └───< PEDIDOS
                │
                └───< DETALLES_PEDIDO >─── VIDEOJUEGOS
Tablas
Tabla	Descripción
clientes	Información de clientes
videojuegos	Catálogo de productos
pedidos	Pedidos realizados
detalles_pedido	Videojuegos incluidos en cada pedido
Conceptos trabajados
Relaciones 1:N
Relaciones N:M
Claves primarias
Claves foráneas
Restricciones CHECK
Restricciones UNIQUE
Integridad referencial
Consultas JOIN
🚀 Instalación
Clonar el repositorio
git clone https://github.com/tu-usuario/curso-bases-datos-mysql.git
Acceder al proyecto
cd curso-bases-datos-mysql
Ejecutar los scripts
Abrir MySQL Workbench.
Crear una nueva base de datos.
Abrir el archivo .sql correspondiente.
Ejecutar el script completo.
💡 Habilidades Desarrolladas
A través de las prácticas y proyectos incluidos en este repositorio se desarrollan competencias relacionadas con:

Diseño de bases de datos.
Modelado relacional.
Programación SQL.
Administración de bases de datos.
Optimización de consultas.
Integridad y consistencia de datos.
🎓 Público Objetivo
Estudiantes de DAM.
Estudiantes de DAW.
Cursos de especialización TIC.
Profesionales que desean reforzar SQL.
Personas que comienzan en la administración de bases de datos.
📈 Próximas Incorporaciones
Bases de datos para gestión empresarial.
Casos prácticos de e-commerce.
Optimización mediante índices.
Transacciones.
Vistas avanzadas.
Seguridad y auditoría.
👨‍💻 Autor
Carlos Arias

Repositorio creado con fines formativos para el aprendizaje y la práctica de bases de datos relacionales utilizando MySQL.

⭐ Si este contenido te resulta útil, considera dejar una estrella en el repositorio.
