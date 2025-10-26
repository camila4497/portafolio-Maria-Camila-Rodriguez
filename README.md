# Portafolio Web – Maria Camila Rodriguez Ortiz

Este proyecto corresponde a la **"Actividad 5 Desarrollo de página web personal con html, css , javascript y framework"**, en la cual se implementa un **sitio web personal tipo portafolio** utilizando **HTML5**, **CSS3**, **Bootstrap (tema Lux de Bootswatch)** y **JavaScript**.  
El sitio tiene como objetivo mostrar los proyectos desarrollados durante el proceso de formación y aplicar validaciones con JavaScript según los lineamientos de la guía.

## Estructura del Proyecto
Portafolio/
├── css/
│ ├── bootstrap.min.css # Tema Lux de Bootswatch
│ ├── all.min.css # Estilos de Font Awesome
│ ├── styles.css # Estilos personalizados
├── js/
│ ├── bootstrap.bundle.min.js # Librería Bootstrap con Popper
│ ├── jquery.min.js # Librería jQuery
│ ├── scripts.js # Archivo JS adicional 
│
├── img/
│ ├── 1000178425.jpeg # foto de perfil
├── index.html # Página principal del portafolio
├── projects.html # Página de proyectos con modales


###  Características Principales

### **1. Página principal (`index.html`)**
- Presenta el nombre, foto e introducción personal.  
- Sección **“Sobre mí”** con una descripción detallada.  
- Módulo de **habilidades técnicas** utilizando íconos de **Font Awesome**.  
- Sección de **contacto** con enlaces a redes (WhatsApp, LinkedIn, Email y GitHub).  
- Incluye un **formulario con validación en JavaScript** que comprueba:
  - Nombre no vacío.  
  - Correo válido.  
  - Motivo seleccionado.  
  - Aceptación de términos.  

### **2. Página de proyectos (`projects.html`)**
- Muestra tres proyectos destacados en formato de tarjetas (`cards`).  
- Cada proyecto tiene un **modal de video** desde YouTube.  
- Implementa JavaScript para **pausar el video automáticamente** al cerrar el modal.  

### **3. Diseño**
- Tema visual: **Bootswatch – Lux**.  
- Diseño adaptable con **Bootstrap 5**.  

### **4. Tecnologías utilizadas**
- **HTML5** – Estructura de páginas.  
- **CSS3 / Bootstrap 5 (Lux)** – Estilos y diseño responsivo.  
- **Font Awesome 6.4.2** – Íconos personalizados.  
- **JavaScript** – Validación de formulario y control de modales.  
