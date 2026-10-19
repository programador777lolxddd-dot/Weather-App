<div align="center">

<!-- Header ultra-vibrante -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:FF007F,50:8A2BE2,100:00B4DB&height=220&section=header&text=Weather-App&fontSize=65&fontColor=ffffff&animation=twinkling&fontAlignY=35&desc=Liquid%20Glass%20Experience&descAlignY=55&descSize=20" width="100%"/>

<br/>

<!-- Typing SVG corregido y centrado -->
<a href="https://github.com/programador777lolxddd-dot/Weather-App">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=00B4DB&center=true&vCenter=true&width=800&height=120&lines=%F0%9F%8C%A6+El+clima+como+nunca+lo+has+visto;%F0%9F%A7%8A+Liquid+Glass+%2B+Efectos+Visuales;%E2%9A%A1+HTML+%C2%B7+CSS+%C2%B7+JavaScript" alt="Typing SVG" />
</a>

<br/><br/>

<!-- Badges unificados y ordenados -->
<p>
  <img src="https://img.shields.io/badge/Estado-En_Desarrollo_🚧-yellow?style=for-the-badge&labelColor=0d1b2a" />
  <img src="https://img.shields.io/badge/Versión-1.0.0-00b4db?style=for-the-badge&labelColor=0d1b2a" />
  <img src="https://img.shields.io/badge/Licencia-MIT-green?style=for-the-badge&labelColor=0d1b2a" />
</p>

<p>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/OpenWeather-eb6e4b?style=flat-square&logo=openweathermap&logoColor=white" />
</p>

### 🌟 Una experiencia meteorológica de otro nivel 🌟

</div>

---

## 📖 Sobre el Proyecto

**Weather-App** no es solo otra aplicación del clima; es una exploración de interfaces de usuario modernas. El proyecto nace con el objetivo de combinar la **utilidad** de un servicio meteorológico en tiempo real con un **diseño visual de vanguardia** basado en el *Glassmorphism* y el *Liquid Glass*.

A diferencia de las aplicaciones tradicionales con fondos planos y aburridos, aquí cada tarjeta, panel y botón utiliza transparencias, desenfoques de fondo (`backdrop-filter`) y bordes brillantes para crear una sensación de **profundidad y fluidez**, como si estuvieras interactuando con cristal líquido.

> 💡 *El proyecto se encuentra en desarrollo activo. Actualmente ofrece el clima actual y búsqueda por ciudades, pero el objetivo a largo plazo es convertirlo en una PWA (Progressive Web App) completa.*

---

## ✨ Características Principales

<table>
<tr>
<td width="50%">

### 🎨 Interfaz y Diseño (UI/UX)
- 🧊 **Efecto Liquid Glass**: Implementación avanzada de CSS para simular vidrio esmerilado.
- 🌈 **Efectos Dinámicos**: Animaciones fluidas y transiciones al interactuar con la app.
- 📱 **100% Responsive**: Adaptado meticulosamente para móviles, tablets y monitores 4K.
- 🌙 **Diseño Inmersivo**: Fondos dinámicos que se adaptan a la hora del día.
- 🔤 **Tipografía Moderna**: Fuentes legibles y estilizadas para una lectura fácil.

</td>
<td width="50%">

### ⚙️ Funcionalidad (Backend & Lógica)
- 🌡️ **Datos en Tiempo Real**: Temperatura, sensación térmica y humedad exacta.
- 💨 **Detalles del Viento**: Velocidad, dirección y ráfagas.
- 📊 **Métricas Atmosféricas**: Presión, visibilidad y punto de rocío.
- 🔍 **Buscador Inteligente**: Encuentra el clima de cualquier ciudad del mundo.
- 📍 **Geolocalización**: Detección automática de tu ubicación actual.
- 🔄 **Manejo de Errores**: Interfaz amigable si falla la conexión o la API.

</td>
</tr>
</table>

---

## 🛠️ Stack Tecnológico

Este proyecto fue construido priorizando el rendimiento y la personalización manual del diseño:

| Tecnología | Uso en el Proyecto |
| :--- | :--- |
| **HTML5** | Estructura semántica y accesible del sitio. |
| **CSS3 (Vanilla)** | Estilos, Glassmorphism (`backdrop-filter`), Grid, Flexbox y animaciones `@keyframes`. |
| **JavaScript (Vanilla)** | Lógica de la aplicación, manipulación del DOM, llamadas `fetch` a la API. |
| **OpenWeather API** | Proveedor de los datos meteorológicos globales. |
| **Git & GitHub** | Control de versiones y alojamiento del código. |

---

## 🚀 Requisitos Previos

Antes de instalar y ejecutar este proyecto, asegúrate de tener:
1. Un navegador web moderno (Chrome, Firefox, Safari o Edge).
2. Una **API Key** gratuita de [OpenWeatherMap](https://openweathermap.org/api) (necesaria para obtener los datos del clima).
3. *(Opcional)* Un servidor local como [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) en VS Code para evitar problemas de CORS.

---

## 📦 Instalación y Configuración

Sigue estos pasos para clonar y configurar el proyecto localmente:

**1. Clona este repositorio:**
```bash
git clone https://github.com/programador777lolxddd-dot/Weather-App.git
cd Weather-App
```

**2. Configura tu API Key:**
Abre el archivo principal de JavaScript (usualmente `js/api.js` o `js/app.js`) y busca la constante destinada a la API Key. 
```javascript
// Reemplaza 'TU_API_KEY_AQUI' con tu clave real
const API_KEY = 'TU_API_KEY_AQUI'; 
```
> ⚠️ **Importante:** Si planeas subir este proyecto a un repositorio público, considera usar variables de entorno o archivos `.env` para no exponer tu clave.

**3. Ejecuta la aplicación:**
Si estás usando VS Code, haz clic derecho en `index.html` y selecciona **"Open with Live Server"**. 
Si no, simplemente abre el archivo `index.html` en tu navegador (aunque algunas APIs requieren `http://` o `https://` para funcionar, por lo que se recomienda el servidor local).

---

## 📂 Estructura del Proyecto

Así está organizado el código fuente de la aplicación:

```text
Weather-App/
│
├── 📄 index.html          # Archivo principal y estructura de la interfaz
│
├── 📂 css/
│   ├── 🎨 styles.css      # Estilos base, layout y responsive
│   └── 🧊 glass.css       # Efectos de cristal, animaciones y gradientes
│
├── 📂 js/
│   ├── ⚙️ app.js          # Lógica de la UI y eventos del usuario
│   ├── 🔌 api.js          # Conexión y manejo de datos de OpenWeather
│   └── 🛠️ utils.js        # Funciones de ayuda (ej. conversión de fechas)
│
├── 📂 assets/             # Recursos gráficos
│   ├── 🖼️ images/         # Fondos, iconos del clima
│   └── 🔤 fonts/          # Fuentes de Google Fonts o locales
│
├── 🚫 .gitignore          # Archivos ignorados por Git (ej. .env)
├── 📜 LICENSE             # Licencia MIT
└── 📖 README.md           # Este archivo
```

---

## 🗺️ Roadmap

- [x] Estructura base y maquetación HTML.
- [x] Implementación del diseño Liquid Glass con CSS.
- [x] Integración con la API de OpenWeather.
- [x] Buscador de ciudades y geolocalización.
- [ ] **Añadir más efectos visuales y animaciones líquidas.**
- [ ] Implementar pronóstico extendido (5 días).
- [ ] Añadir selector de unidades (°C / °F).
- [ ] Soporte para múltiples idiomas (ES / EN).
- [ ] Convertir la app en una PWA instalable.

---

## ❓ Preguntas Frecuentes (FAQ)

<details>
<summary><b>¿Por qué la app no carga el clima? (Haz clic aquí)</b></summary>
<br>
Asegúrate de haber configurado correctamente tu API Key de OpenWeatherMap en el archivo JavaScript. Además, verifica que hayas esperado al menos 10 minutos después de crear tu clave en OpenWeather (las nuevas claves tardan un poco en activarse).
</details>

<details>
<summary><b>¿Puedo usar esta app en mi propio proyecto?</b></summary>
<br>
¡Claro! El proyecto está bajo la licencia MIT. Puedes clonarlo, modificarlo y usarlo como portafolio o base para tus propias ideas.
</details>

---

## 🤝 Contribuciones

¡Las contribuciones son lo que hacen que la comunidad open source sea un lugar increíble para aprender, inspirar y crear! Cualquier aporte que hagas es **enormemente apreciado**.

Si tienes ideas para mejorar los efectos de "Liquid Glass" o quieres añadir nuevas funcionalidades:

1. Haz un **Fork** del proyecto.
2. Crea tu rama de características (`git checkout -b feature/NuevoEfecto`).
3. Haz un **Commit** de tus cambios (`git commit -m 'Añade nuevo efecto de cristal'`).
4. Haz un **Push** a la rama (`git push origin feature/NuevoEfecto`).
5. Abre un **Pull Request**.

También puedes abrir un **Issue** si encuentras algún bug.

---

## 📄 Licencia

Distribuido bajo la Licencia **MIT**. Consulta el archivo `LICENSE` para más información.

<br/>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00B4DB,100:FF007F&height=120&section=footer" width="100%"/>

**Hecho con ❤️ y mucho "Liquid Glass" por [@programador777lolxddd-dot](https://github.com/programador777lolxddd-dot)**
</div>
