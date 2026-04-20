# 🏃‍♂️ AlejApp_Run_Track

**Control diario de trote, IMC, gráficos de rendimiento y consejos de nutrición**

![Demo](https://img.shields.io/badge/status-activo-brightgreen) ![License](https://img.shields.io/badge/license-MIT-blue) ![HTML](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## 📝 Descripción

**AlejApp_Run_Track** es una aplicación web autocontenida (un solo archivo HTML/CSS/JS) que te permite:

- Registrar tu perfil (peso, altura, fecha de nacimiento) y calcular tu **IMC actual y objetivo** (rango saludable).
- Agregar sesiones diarias de trote: fecha, distancia (km), tiempo (min) y peso opcional.
- Visualizar **dos gráficos de líneas** con datos de los últimos 90 días:
  - Distancia recorrida por fecha.
  - Evolución del peso.
- Recibir una **frase motivacional** diferente cada día.
- Obtener un **tip de nutrición** diario (frutas, verduras, proteínas animales y pescado).
- Ver las últimas 5 sesiones con opción de eliminar.
- Persistencia total con `localStorage` – no requiere internet después de la primera carga (excepto fuentes y Chart.js CDN).

## 🚀 ¿Cómo usar la app?

1. **Abre el archivo** `AlejApp_Run_Track.html` en cualquier navegador moderno (Chrome, Edge, Firefox).
2. **Completa tu perfil** inicial: peso, altura, fecha de nacimiento. La app calculará automáticamente tu IMC objetivo.
3. **Registra tus trotes** cada día usando el formulario. El peso es opcional (si no lo ingresas, se mantiene el último registrado).
4. **Observa los gráficos** que se actualizan en tiempo real mostrando solo los últimos 90 días.
5. **Lee tu frase y tip diario** – cambian cada vez que guardas una sesión o recargas la página.
6. **Elimina sesiones** desde la tabla de historial si es necesario.

## 📁 Estructura del proyecto

El proyecto es **un único archivo HTML** que contiene:

- CSS interno (diseño futurista con glassmorphism, neones y responsive).
- JavaScript interno (lógica de estado, gráficos Chart.js, almacenamiento local).
- Fuentes de Google (Poppins, Inter) y Chart.js desde CDN.

No se necesita ningún servidor ni instalación adicional.

## 🛠️ Tecnologías utilizadas

- **HTML5 / CSS3** – Estructura y estilos.
- **JavaScript ES6** – Lógica y persistencia.
- **Chart.js** – Gráficos de líneas dinámicos.
- **localStorage** – Almacenamiento de perfil y sesiones.
- **Google Fonts** – Tipografía moderna.

## 📦 Instalación y ejecución local

1. **Descarga** el archivo `AlejApp_Run_Track.html` desde este repositorio.
2. **Guárdalo** en tu computadora.
3. **Haz doble clic** para abrirlo en tu navegador.
4. ¡Listo! No requiere más pasos.

## 🌐 Publicar en línea (GitHub Pages)

Si quieres compartir la app como un sitio web público:

1. Sube este repositorio a GitHub.
2. Ve a **Settings > Pages**.
3. En "Branch", selecciona `main` y guarda.
4. En unos minutos, tu app estará disponible en:  
   `https://TU_USUARIO.github.io/AlejApp_Run_Track/`

## 🤝 Contribuciones

¿Quieres mejorar la app? ¡Eres bienvenido! Puedes:

- Añadir más frases motivacionales o tips de nutrición.
- Mejorar los gráficos (por ejemplo, añadir ritmo por km).
- Implementar exportación de datos a CSV.
- Crear una versión con modo oscuro/claro.

Solo haz un **fork** del repositorio, crea una rama con tu mejora y envía un **pull request**.

## 📄 Licencia

Este proyecto se distribuye bajo la licencia **MIT**. Puedes usarlo, modificarlo y compartirlo libremente.

## 📧 Contacto

Desarrollado por [Tu nombre / Alejandro] – [opcional: tu correo o perfil de GitHub]

---

⭐ **Si te gusta esta app, no olvides darle una estrella en GitHub.** ¡Gracias por usarla!
