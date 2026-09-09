# Seminario-26B
## 1. Problema
La creciente dependencia de la tecnología en ámbitos personales, académicos y laborales ha incrementado la exposición de los usuarios a riesgos cibernéticos, en donde la ingeniería social ha permitido que el phishing se haya vuelto más constante, generando pérdidas económicas, robo de identidad/información, afectaciones psicológicas y el deterioro general de la seguridad en línea.

## 2. Objetivo general y objetivos particulares

### 2.1 Objetivo general
Desarrollar una extensión para los navegadores Google Chrome y Mozilla Firefox con la capacidad de analizar y clasificar enlaces antes de su apertura, orientada a disminuir la exposición de los usuarios ante la amenaza del phishing. Está solución ofrecerá un sistema de alerta claro, confiable y accesible que contribuya al fortalecimiento de la seguridad digital.

### 2.2 Objetivos particulares
Analizar técnicas de ingeniería social y phishing así como factores que incrementan la vulnerabilidad de los usuarios.
Desarrollar un sistema automatizado que analiza enlaces y los evalúa considerando fechas de creación, validez de certificados, redirecciones, uso de acortadores, similitud de dominios, entre otros.
Implementar un mecanismo de alerta visual intuitivo por medio de semáforos que facilite la interpretación de los resultados al usuario sin que requiera de conocimientos técnicos avanzados.
Integrar consultas a bases de datos sobre la reputación de dominios, habilitando una función colaborativa para que los usuarios puedan reportar enlaces sospechosos, permitiendo así tener una actualización continua ante nuevos enlaces y amenazas.

## 3. Alcance
El proyecto comprende el diseño, construcción y pruebas de una extensión para navegadores web orientada al análisis preventivo de enlaces sospechosos antes de su apertura.

## 4. Fuera de alcance
La extensión no funcionará fuera de los navegadores web, por lo que abrir enlaces en aplicaciones externas no permitirá que la extensión las analice. Además, la extensión no detendrá al usuario de seguir a la página marcada como riesgosa, solo dará el aviso en pantalla de forma clara.
La extensión no reemplazará soluciones profesionales de ciberseguridad como antivirus.
No analizará archivos descargados o detectar malware dentro de programas.

## 5. MVP
El producto mínimo viable será una primera versión de la extensión que permita demostrar la viabilidad de la solución que analice enlaces y advierta al usuario sobre posibles riesgos antes de acceder.
Las funcionalidades mínimas son:
Extensión funcional en un navegador.
Análisis básico de enlaces, considerando indicadores de riesgo como acortadores de enlaces, presencia de patrones sospechosos, uso de HTTP en lugar de HTTPS, dominios con estructuras raras y similitudes básicas con dominios conocidos.
Clasificará el riesgo en tres niveles: 
Bajo riesgo (verde): no se detectaron indicadores de riesgo.
Riesgo medio (amarillo): se detectaron características sospechosas.
Riesgo alto (rojo): se detectaron múltiples indicadores de riesgo.
La extensión mostrará una alerta visual clara indicando el nivel de riesgo, el color correspondiente y una explicación sencilla de los riesgos detectados.
La extensión no almacenará información personal ni el historial de navegación del usuario.
