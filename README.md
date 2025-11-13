## 🐾 RTK VET SYSTEM  
**Software de gestión para clínicas veterinarias**

RTK VET SYSTEM es una aplicación de escritorio desarrollada en **Java (Swing)** que permite administrar de forma integral los procesos de una clínica veterinaria.  
Gestiona pacientes, propietarios, citas, tratamientos y reportes, utilizando una **base de datos embebida H2** que no requiere configuración ni instalación adicional.

---

### 🧠 Descripción general  

Este proyecto forma parte de **RTK (Robtiktronikx)** y fue creado con fines **educativos y demostrativos**.  
RTK VET SYSTEM aplica los principios de **Programación Orientada a Objetos (POO)**, el patrón **MVC (Modelo–Vista–Controlador)** y el manejo de **bases de datos relacionales** mediante H2, todo dentro de un entorno **Java Swing** para la interfaz gráfica.  

El software se entrega en formato `.jar` listo para ejecutar, lo que lo hace completamente portátil y funcional en cualquier sistema con Java instalado.

---

### ⚙️ Características principales  

- 🐶 **Gestión de pacientes:** registro y edición de información de mascotas y sus dueños.  
- 📅 **Control de citas:** creación, modificación y cancelación de citas veterinarias.  
- 💊 **Historial médico:** registro de diagnósticos, tratamientos y observaciones.  
- 💾 **Base de datos embebida H2:** almacenamiento local sin necesidad de servidores externos.  
- 📊 **Reportes internos:** consultas y reportes básicos sobre atención y pacientes.  
- 🔐 **Control de acceso:** usuario administrador configurado en el sistema.  
- 🖥️ **Interfaz intuitiva:** desarrollada completamente en **Java Swing**.  
- 🚫 **Uso no comercial:** el software está licenciado para fines personales y educativos.

---

### 🚀 Ejecución del sistema  

#### 🧩 Requisitos previos  
- **Java JDK 17** o superior instalado en el equipo.  
  Verifica la instalación con:
  ```bash
  java -version
  ```

#### ▶️ Ejecución del programa  
1. Descarga el archivo `RTK-VET-SYSTEM.jar` desde la carpeta principal del repositorio o desde la sección **Releases**.  
2. Guárdalo en cualquier carpeta local.  
3. Ejecuta el archivo:  
   - Doble clic sobre el `.jar`, o  
   - Desde la terminal:
     ```bash
     java -jar RTK-VET-SYSTEM.jar
     ```

💡 *El sistema creará automáticamente la base de datos H2 local la primera vez que se ejecute.*

---

### 🧩 Estructura del proyecto  

```
RTK-VET-SYSTEM/
├── app/                      # Punto de entrada (App.java)
├── model/                    # Clases de negocio y entidades
├── view/                     # Interfaz gráfica (Swing)
├── controller/               # Lógica que conecta modelo y vista
├── RTK-VET-SYSTEM.jar        # Archivo ejecutable principal
├── build-jar.ps1             # Script de construcción del .jar
├── Requerimientos funcionales y no funcionales.pdf
└── LICENSE                   # Licencia personalizada (uso no comercial)
```

---

### 💾 Base de datos  

RTK VET SYSTEM utiliza **H2 Database** en modo embebido, lo que permite:
- Portabilidad total del proyecto.  
- Funcionamiento sin conexión a internet.  
- Consultas SQL estándar.  
- Archivos de base de datos almacenados localmente dentro del proyecto.  

---

### 🧠 Arquitectura y principios  

El proyecto aplica el patrón **MVC (Modelo–Vista–Controlador)**:  
- **Modelo:** define la estructura de datos (pacientes, citas, usuarios).  
- **Vista:** interfaz creada con **Java Swing**.  
- **Controlador:** coordina la interacción entre vista y modelo.

Además, implementa conceptos de:
- **Encapsulamiento y herencia (POO).**  
- **Persistencia mediante JDBC (conexión a H2).**  
- **Modularidad y separación de responsabilidades.**

---

### 🧾 Licencia  

Este software está protegido por una **Licencia Personalizada de Uso No Comercial**.  
Está prohibida su venta, distribución o uso con fines de lucro sin autorización expresa.  

📄 Ver archivo [`LICENSE`](./LICENSE)  
© 2025 **Juan Villegas** — Todos los derechos reservados.

---

### 🧰 Créditos técnicos  

**Lenguaje principal:**  
- Java 17  

**Frameworks y librerías:**  
- [Java Swing](https://docs.oracle.com/javase/tutorial/uiswing/) — Interfaz gráfica.  
- [H2 Database Engine](https://www.h2database.com/) — Base de datos embebida.  
- JDBC (Java Database Connectivity) — Conexión a la base de datos.  

**Entorno de desarrollo:**  
- Visual Studio Code (con extensión Java)  
- PowerShell scripts (`build-jar.ps1`, `run-vscode.ps1`) para automatizar la compilación.  

**Arquitectura:**  
- Patrón MVC (Modelo–Vista–Controlador).  
- Diseño modular orientado a objetos.

---

### ✉️ Autor  

**Juan Villegas**  
Proyecto **RTK Soluciones — Robtiktronikx Soluciones**  
📧 *contacto.juanesvm@gmail.com / robotiktronikx@gmail.com*  
