# Registro de Actividades, Gráficos y Mapas con Google Maps

## Descripción del Proyecto

Este proyecto es una aplicación web que permite a los usuarios:
1. Registrar actividades relacionadas con su bienestar personal, como ejercicio, alimentación y descanso.
2. Visualizar gráficos basados en los datos registrados.
3. Ver su ubicación actual en un mapa junto con los parques cercanos usando Google Maps.

El objetivo principal es ayudar a los usuarios a llevar un seguimiento de sus actividades y encontrar recursos cercanos para mejorar su bienestar.

---

## Características Principales

- **Registro de Actividades:** Permite ingresar actividades diarias con su nombre, descripción y tiempo dedicado.
- **Gráficos Dinámicos:** Muestra gráficos interactivos que reflejan las actividades registradas.
- **Mapa con Parques Cercanos:** Utiliza la API de Google Maps para mostrar la ubicación actual del usuario y marcar parques cercanos en un radio de 5 km.

---

## Tecnologías Utilizadas

- **HTML5** y **CSS3**: Para la estructura y el diseño de la aplicación.
- **JavaScript (ES6)**: Para la lógica de interacción y la integración con las APIs.
- **Google Maps API**: Para la visualización de la ubicación y búsqueda de lugares cercanos.
- **Chart.js**: Para la generación de gráficos dinámicos e interactivos.

---

## Instrucciones para Usar la Aplicación

1. **Abrir el Archivo Principal**: Abre el archivo `index.html` en tu navegador para acceder al registro de actividades.
2. **Registrar Actividades**: Completa los campos del formulario para registrar una actividad y haz clic en "Agregar".
3. **Ver los Gráficos**: Haz clic en el botón "Ver Gráficos" para visualizar los datos registrados en forma de gráficos.
4. **Ver el Mapa**: En la página de gráficos, haz clic en "Ver Mapa" para acceder al mapa con los parques cercanos.

---

## Cómo Funciona el Proyecto

1. **Formulario de Registro**:
   - Los datos ingresados en el formulario se almacenan temporalmente en la memoria del navegador (localStorage).
2. **Gráficos Interactivos**:
   - Se generan dinámicamente con los datos del registro utilizando Chart.js.
3. **Mapa con Ubicación y Parques**:
   - Usa la geolocalización del navegador para centrar el mapa en la ubicación del usuario.
   - Muestra parques cercanos usando Google Maps Places API.

---

## Enlace al Repositorio

Puedes encontrar el código fuente completo del proyecto en el siguiente enlace:  
https://github.com/juanse1229/DesarrolloWeb.git

---

## Autor

Proyecto realizado por Juan Sebastian Rojas Gallego.
