# ⚽ Reglamento Virtual Interactivo: RoboFútbol

<div align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
</div>

<br>

## 📖 Descripción General

El **Reglamento Virtual Interactivo de RoboFútbol** es una experiencia web educativa, interactiva y gamificada creada para presentar de forma dinámica el **Reglamento Oficial de Competencia del Torneo RoboFútbol** de **TecnoAcademia Manizales**, en articulación con la **Universidad de Caldas** y el **Servicio Nacional de Aprendizaje (SENA)**.

En lugar de presentar el reglamento únicamente como un documento estático, el proyecto organiza sus contenidos en un recorrido modular. Desde un dashboard central, el usuario puede avanzar por los diferentes módulos, consultar el estado de cada sección, acumular progreso y desbloquear insignias asociadas a su recorrido.

La experiencia está planteada como un **reglamento virtual interactivo y gamificado**, no como un curso convencional.


## 🚀 Acceso al Proyecto
Puedes visualizar la plataforma en vivo aquí: 👉 https://altarians05.github.io/ReglamentoSumoBot/index.html


## ✨ Características Principales

* **Dashboard central:** El archivo `index.html` funciona como tablero principal para acceder a los módulos del reglamento.
* **Contenido modular:** El reglamento está organizado en **9 módulos/secciones (0 a 8)**, con contenidos específicos sobre disposiciones generales, robot, cancha y balón, sistema de competencia, desarrollo del partido, situaciones especiales, desempates, faltas y sanciones, y palabras clave.
* **Sistema de progreso:** El avance se calcula a partir de los módulos completados y se representa mediante una barra de progreso global. El estado se conserva temporalmente mediante `sessionStorage`.
* **Desbloqueo progresivo:** Cada módulo posee un estado visual que puede indicar misión cumplida, módulo en curso o acceso restringido. El dashboard controla el acceso antes de abrir el módulo correspondiente.
* **Sistema de niveles:** El progreso determina un nivel dentro de la experiencia: **Piloto Novato**, **Constructor Táctico**, **Ingeniero de Juego**, **Estratega de la Cancha**, **Capitán Supremo** y, al completar el recorrido, **Leyenda de la Cancha**.
* **Sistema de insignias:** Se muestran cinco insignias —Bronce, Plata, Oro, Esmeralda y Rubí— que se activan según la finalización de módulos específicos.
* **Experiencia de finalización:** Al completar todos los módulos aparece un mensaje de logro y una animación final con fuegos artificiales.
* **Diseño institucional y responsivo:** La interfaz utiliza la identidad visual basada en la paleta SENA y presenta referencias institucionales de **SENA, TecnoAcademia Manizales y Universidad de Caldas**, con adaptación para pantallas de escritorio y dispositivos móviles.
* **Recursos gráficos interactivos:** El dashboard utiliza fondos, iconografía, insignias y un personaje de apoyo visual para reforzar la experiencia de navegación y gamificación.

## 📂 Estructura del Proyecto

```text
📁 Reglamento-Virtual-RoboFutbol/
├── 📄 index.html
│   └── Dashboard principal y centro de navegación
├── 📄 modulo0.html
├── 📄 modulo1.html
├── 📄 modulo2.html
├── 📄 modulo3.html
├── 📄 modulo4.html
├── 📄 modulo5.html
├── 📄 modulo6.html
├── 📄 modulo7.html
├── 📄 modulo8.html
│   └── Módulos enlazados desde el dashboard
└── 📁 imagenes/
    ├── 📁 Logos/
    │   ├── 📄 sena.png
    │   └── 📄 tecnoacademia.jpeg
    ├── 📁 Insignias/
    │   └── 📁 insignias-mohs/
    │       ├── 📄 00-insignias-mohs-bronce.png
    │       ├── 📄 01-insignias-mohs-plata.png
    │       ├── 📄 02-insignias-mohs-oro.png
    │       ├── 📄 03-insignias-mohs-esmeralda.png
    │       └── 📄 04-insignias-mohs-rubi.png
    ├── 📁 Fondos/
    │   ├── 📄 Titulos_Mesa de trabajo 1 copia.png
    │   ├── 📄 academia_Makers_exterior_1.png
    │   ├── 📄 Bosque_1.png
    │   ├── 📄 Fondo_futurista.png
    │   ├── 📄 Fondo_ingenieria.png
    │   ├── 📄 Fondo_laboratorio.png
    │   ├── 📄 salón_1.png
    │   ├── 📄 aula tecnologica.png
    │   └── 📄 salon de quimica.png
    └── 📁 Personajes/
        └── 📁 Maker/
            └── 📄 facilitador ingeniería y diseño.png
```

> Los nombres de los recursos anteriores corresponden a las rutas utilizadas por el `index.html` para construir su interfaz y navegación.

## 🚀 Instalación y Uso

El proyecto es una aplicación web estática y no requiere un backend, una base de datos ni un sistema de dependencias para funcionar.

1. **Ubica todos los archivos del proyecto** conservando su estructura de carpetas y nombres.
2. **Abre `index.html`** en un navegador web moderno como Google Chrome, Mozilla Firefox o Microsoft Edge.
3. **Navega por los módulos** desde el dashboard. El sistema controla qué secciones están disponibles según el estado de progreso almacenado durante la sesión.
4. **Completa el recorrido** para actualizar el progreso, activar las insignias correspondientes y alcanzar el nivel final de la experiencia.

## 🛠️ Tecnologías Utilizadas

* **HTML5:** Estructura de la interfaz principal y de los contenidos modulares.
* **CSS3:** Estilos personalizados, variables de color, tarjetas, estados visuales, animaciones, diseño responsivo y efectos de interfaz.
* **JavaScript (ES6):** Gestión de navegación, estado de los módulos, cálculo de progreso, niveles, insignias, almacenamiento temporal y animación final.
* **`sessionStorage`:** Persistencia temporal del estado de la experiencia dentro de la sesión del navegador.
* **Font Awesome 6.4.0:** Iconografía utilizada en tarjetas, estados y elementos de navegación.
* **Google Fonts:** Tipografías **Montserrat** y **Roboto**.

## 🎮 Organización de los Módulos

El dashboard presenta las siguientes secciones del reglamento:

| Módulo | Contenido |
|---|---|
| **00** | Disposiciones generales |
| **01** | Especificaciones técnicas del robot |
| **02** | Verificación del robot, cancha y balón |
| **03** | Sistema de competencia y sorteos |
| **04** | Estructura y desarrollo del partido |
| **05** | Situaciones especiales y fallas |
| **06** | Criterios objetivos de desempate |
| **07** | Acciones permitidas, faltas y sanciones |
| **08** | Palabras clave |

El módulo **08** está planteado como sección de **consulta**. En el estado inicial del dashboard también se encuentran disponibles los módulos **00, 07 y 08**, mientras que los demás se gestionan mediante el sistema de desbloqueo.

## 🏅 Progreso, Niveles e Insignias

La experiencia utiliza nueve módulos como base del progreso global. El porcentaje aumenta conforme se registran módulos completados.

Los niveles definidos en el dashboard son:

- **Piloto Novato:** estado inicial.
- **Constructor Táctico:** desde el 20 %.
- **Ingeniero de Juego:** desde el 40 %.
- **Estratega de la Cancha:** desde el 60 %.
- **Capitán Supremo:** desde el 80 %.
- **Leyenda de la Cancha:** al alcanzar el 100 %.

Las cinco insignias se asocian a la finalización de los módulos **02, 03, 04, 05 y 06**, respectivamente:

**Bronce — Debutante · Plata — Técnico de Juego · Oro — Goleador · Esmeralda — Estratega · Rubí — Leyenda de la Cancha**

Al completar el 100 % del recorrido se muestra además una pantalla de felicitación con el mensaje de **“Leyenda de la Cancha”** y una animación de fuegos artificiales.

## 🤝 Contribuciones

El proyecto está orientado al uso formativo e institucional. Para mantener una organización adecuada de los cambios, las contribuciones pueden gestionarse mediante el flujo habitual de GitHub:

1. Crear un *Fork* del repositorio.
2. Crear una rama para la mejora.
3. Realizar y probar los cambios.
4. Hacer *commit* de la modificación.
5. Enviar un *Pull Request* para revisión.

---

*Desarrollado para apoyar el aprendizaje del reglamento y el fortalecimiento de habilidades STEM mediante la robótica competitiva.*
