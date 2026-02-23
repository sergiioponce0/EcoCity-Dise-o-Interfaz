# 🏙️ EcoCity - Diseño UI/UX y Gamificación

Bienvenido al repositorio de diseño de **EcoCity**, una aplicación móvil Android enmarcada en la iniciativa "Ciudad Inteligente". Este documento detalla la arquitectura de la información, la experiencia de usuario (UX) y el diseño de la interfaz (UI) de la plataforma.

El objetivo visual de EcoCity es empoderar a los ciudadanos mediante una herramienta accesible, recompensando su participación activa para mejorar el entorno urbano.

---

## 🎮 UX Cívica y Gamificación (Novedad)

Para asegurar la retención de usuarios y fomentar la participación ciudadana continua, EcoCity implementa un sistema de gamificación integrado orgánicamente en la interfaz principal:

* **Eco-Points:** Sistema de recompensas donde el usuario gana puntos por cada incidencia reportada y validada.
* **Objetivos Semanales:** Barras de progreso visuales que motivan al ciudadano a mantener un nivel de participación activo.
* **Eco-Tip del Día:** Espacio dinámico que educa al usuario sobre sostenibilidad y civismo (Ej: *"Un bache arreglado a tiempo previene daños mayores..."*).

---

## 🎨 Filosofía de Diseño y Estética

El diseño de EcoCity se sostiene sobre pilares de accesibilidad y modernidad:

1. **Navegación Intuitiva (Bottom Nav & FAB):** Estructura centralizada con una barra de navegación inferior y un *Floating Action Button* (FAB) sobredimensionado y central. Esto permite reportar una incidencia al instante con el pulgar.
2. **Sistema de Tarjetas (*CardViews*):** Uso de contenedores con esquinas redondeadas y sombras suaves para agrupar la información (estadísticas, reportes, botones de acción multimedia), reduciendo el ruido visual.
3. **Filtros Dinámicos (Chips):** Categorización accesible mediante "Chips" (Residuos, Iluminación, Vías, etc.) que permiten al ciudadano filtrar el *feed* de su ciudad con un solo toque.

---

## 🖌️ Paleta de Colores y Tipografía

La interfaz utiliza un diseño limpio sobre fondos claros (tonos pastel muy sutiles) para maximizar la legibilidad, apoyado en dos colores clave:

* **Verde Sostenible (Éxito y Acción):** Utilizado en cabeceras, botones de confirmación (*Enviar Reporte*) y detalles de gamificación. Transmite ecología y validación.
* **Morado Corporativo (Acento y Contraste):** Aplicado en botones primarios (Ej: *Iniciar Sesión*) y elementos de navegación. Aporta un toque moderno y tecnológico que contrasta perfectamente con el verde.
* **Señalización de Urgencias:** Indicadores laterales de color en cada tarjeta de reporte (Ej: Rojo para nivel "Alta") para una identificación rápida del estado de la ciudad.

---

## 📱 Pantallas Principales

1. **Autenticación (Login/Registro):** Interfaz minimalista con el logotipo en el centro. Incluye campos de texto limpios, botón de acción primario y soporte para inicio de sesión rápido con *Google Sign-In*.
2. **Dashboard Interactivo:** La pantalla central. Aloja la cabecera de bienvenida, las tarjetas de gamificación (Tip, Objetivos, Puntos), la botonera de filtros por categoría y el listado de *Reportes* en formato tarjeta con iconos representativos.
3. **Formulario "Nueva Incidencia":** Diseñado para evitar la fatiga cognitiva. Consta de campos de texto limpios, menús desplegables claros (Categoría, Nivel de Urgencia) y un innovador panel de **Multimedia y Ubicación** distribuido en una cuadrícula de 4 botones (Cámara, Galería, Audio y GPS).

---

## 🔗 Enlaces del Proyecto de Diseño

En los siguientes enlaces se puede consultar el trabajo de prototipado y la defensa del diseño gráfico:

* 🎨 **[Prototipo Interactivo en Figma](https://www.figma.com/make/CApOmmRo0n5dTO5omwxaI6/EcoCity-Incident-Reporting-App?t=a3OiZE21MQhIDv0f-1)**
    > *Contiene los wireframes, flujos de pantalla, paleta de colores y componentes Material Design utilizados.*

* 📊 **[Presentación UI/UX en Canva](https://www.canva.com/design/DAHCFGjVfgI/ZUf8sKgSINA2wheZSoEZyQ/view?utm_content=DAHCFGjVfgI&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=hdeab808e19)**
    > *Diapositivas utilizadas para la exposición de la interfaz, gamificación y estética frente a los requerimientos del proyecto.*

---
*Desarrollado para el proyecto "Ciudad Inteligente" - Módulo de Diseño de Interfaces (DI).*
