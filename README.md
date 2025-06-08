# -SakilaConsoleCRUD-Python-SQLAlchemy-MySQL-
Este proyecto implementa un sistema CRUD profesional en consola utilizando Python, SQLAlchemy y la base de datos de ejemplo Sakila de MySQL. El enfoque está basado en programación orientada a objetos (POO), arquitectura modular y menús interactivos por consola.  ⸻



Este proyecto implementa un sistema CRUD profesional en consola utilizando Python, SQLAlchemy y la base de datos de ejemplo Sakila de MySQL. El enfoque está basado en programación orientada a objetos (POO), arquitectura modular y menús interactivos por consola.

⸻


# 📌 Características principales
	•	CRUD completo para entidades Sakila como:
	•	Actor
	•	Film
	•	Customer
	•	Inventory
	•	Rental
	•	Payment
	•	Staff
	•	Store
	•	Category
	•	Language
	•	Country
	•	Address
	•	Menú principal categorizado por tipo de entidad (Catálogo, Transaccional, Entidades)
	•	DbContext personalizado que gestiona la sesión y el mapeo de entidades
	•	Validación de entradas (ID, campos vacíos, opciones inválidas)
	•	Navegación intuitiva por consola
	•	Visualización tabular de datos usando tabulate
	•	Organización profesional del código por clases y modelos

⸻

# ⚙️ Tecnologías utilizadas
	•	Python 3.12+
	•	SQLAlchemy 2.0+
	•	tabulate
	•	MySQL 
	•	Estilo ANSI/ASCII para menús y colores de consola

# 🧱 Estructura del proyecto

/Models/              → Clases ORM para cada entidad (ActorModel, FilmModel, Base.py , etc.)
/DbContext.py         → Clase personalizada para gestionar la sesión de SQLAlchemy y BD
/main.py              → Menú principal de navegación


# 🚀 Cómo ejecutar el proyecto

	1.	Clona el repositorio:
      git clone https://github.com/tu-usuario/SakilaConsoleCRUD.git
      cd SakilaConsoleCRUD
      
	2.	Instala los requerimientos:
      pip install -r requirements.txt

	3.	Configura tu conexión en DbContext.py:
      engine = create_engine("mysql+mysqlconnector://usuario:clave@localhost/sakila")

	4.	Ejecuta el sistema:
      python main.py


# 📷 Ejemplos de interfaz

 	•	Menú principal con secciones por tipo de entidad
	•	CRUD por consola con validaciones por ID
	•	Visualización en tabla de registros con paginación (200 registros por pantalla)
	•	Mensajes destacados de selección usando colores ANSI


# 📌 Créditos
Desarrollado por:
	•	Norman Yulifer Carrasco Medina
	•	Miguel Mariano Pimentel Alcántara
	•	Miguel Ángel Consoro Guzmán
