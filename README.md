# unidad1fase2game
Este es un proyecto de un juego multiple de arrastrar y soltar, plataforma y sapace invaders con preguntas sobre la unidad 1
 Minijuego Educativo - TEACHUNITED

Un juego educativo web interactivo de 3 niveles desarrollado completamente con tecnologías web estándar (Vanilla JS, HTML5, CSS3). Está diseñado para ser accesible tanto en computadoras de escritorio como en dispositivos móviles, ofreciendo diferentes mecánicas de juego para evaluar y enseñar de forma divertida.

🚀 Características Principales

El proyecto consta de tres niveles con mecánicas únicas:

Nivel 1 - Clasificación (Drag & Drop): Actividad de arrastrar y soltar donde el usuario debe clasificar elementos en sus contenedores correctos.

Nivel 2 - Plataformas (Movimiento y Salto): Un minijuego con físicas 2D básicas donde el jugador debe sortear obstáculos saltando y moviéndose lateralmente.

Nivel 3 - Atrapar/Esquivar: El jugador controla un elemento en la parte inferior de la pantalla y debe moverse de izquierda a derecha para interactuar con objetos que caen.

✨ Otras Funcionalidades

Registro e Identificación: El jugador debe ingresar sus datos antes de comenzar.

Sistema de Puntuación: Registro del progreso y puntaje a lo largo de los 3 niveles.

Sincronización de Datos: Capacidad de enviar (flush) los resultados pendientes a un servidor o base de datos.

Sistema de Notificaciones: Alertas no intrusivas tipo "Toast" para guiar al usuario.

📱 Soporte y Optimización Móvil

El juego ha sido optimizado recientemente para garantizar una excelente experiencia en smartphones y tablets:

Bloqueo de Orientación (Landscape): Si el usuario ingresa desde un móvil en modo vertical (Portrait), una pantalla de bloqueo le solicitará girar el dispositivo para jugar cómodamente.

Polyfill para Touch Drag & Drop: Se utiliza la librería mobile-drag-drop para traducir los toques táctiles del móvil a eventos nativos de arrastrar y soltar de HTML5 en el Nivel 1.

Grid Responsivo: Las zonas de arrastrar y soltar se adaptan a 2 columnas en pantallas pequeñas para facilitar el toque.

Controles Táctiles en Pantalla: Para los Niveles 2 y 3, se activan botones virtuales gigantes y translúcidos en las esquinas inferiores (Izquierda/Derecha para caminar, Arriba para saltar) que no interfieren con la visión del juego pero son fáciles de presionar.

🛠️ Tecnologías Utilizadas

HTML5: Estructura semántica del juego y Canvas.

CSS3: Estilos, variables nativas (:root), animaciones, Flexbox/Grid y Media Queries para la adaptabilidad (Responsive Design).

Vanilla JavaScript: Toda la lógica del juego, motor de físicas ligero, manejo del DOM y eventos. Cero frameworks pesados.

Dependencias Externas:

Mobile Draganddrop para soporte táctil en el Nivel 1.

⚙️ Instalación y Uso

Dado que es un proyecto Front-end estático (Vanilla), no requiere instalación de Node.js, compiladores ni servidores de desarrollo complejos.

Clona o descarga este repositorio/carpeta.

Abre el archivo principal .html (por ejemplo, index.html) directamente en cualquier navegador web moderno (Chrome, Firefox, Safari, Edge).

¡Empieza a jugar!

Nota: Si tu código JavaScript realiza peticiones fetch a una API para enviar los datos de los usuarios, asegúrate de servir el archivo mediante un servidor local (como Live Server en VSCode) para evitar problemas de políticas CORS.

🕹️ Controles

Escritorio (PC):

Nivel 1: Clic izquierdo sostenido (Mouse).

Niveles 2 y 3: Flechas direccionales (←, →) y barra espaciadora (Space) para saltar.

Móvil / Tablet:

Nivel 1: Mantener presionado el dedo sobre la pantalla y arrastrar.

Niveles 2 y 3: Botones táctiles translúcidos en la pantalla.
