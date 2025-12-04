
Codelabs Opcionales - Proyecto Integrador II
================================

Este repositorio contiene diversos codelabs y experimentos desarrollados durante el curso Proyecto Integrador II.
Cada carpeta incluye código, modelos y ejemplos relacionados con técnicas de machine learning, visión por computadora y procesamiento de datos.

------------------------------------------------------------
Estructura del repositorio
------------------------------------------------------------

### Yolo Train Roboflow Universe/
Proyecto de entrenamiento de YOLO usando datasets de Roboflow Universe.

### estafa spam/
Clasificador para detectar mensajes de estafa/spam.

### triage mensajes/
Clasificador para detectar mensajes según categoria: ventas, soporte o queja.
Adicionalmente, se integra este modelo en un servicio sencillo con FastAPI

### Scrapping básico partidos del día
Se realiza scappring a la página de https://www.futbolred.com/parrilla-de-futbol y se obtienen los partidos de fútbol del día, junto
a hora y canal para ver en Colombia.

### example led
Ejercicio que implementa a nivel de software la ejecución de código para encender un led

### mcp nodered demo
Código para implementar código MCP y ejecutarlo desde claude desktop, ejecutar código desde la interfaz del LLM y que se ejecute en nodered
y lograr conexión para realizar ejecuciones en hardware

------------------------------------------------------------
Requisitos
------------------------------------------------------------

1. Tener Python 3.9+ instalado.
2. Crear un entorno virtual (opcional pero recomendado):
```
    python -m venv venv
    source venv/bin/activate  # Linux / Mac
    venv\Scripts\activate     # Windows
```
3. Instalar dependencias:

``
    pip install -r requirements.txt
``

------------------------------------------------------------
Ejecución de los ejemplos
------------------------------------------------------------

Cada carpeta puede ejecutarse de forma independiente.
Dentro de cada carpeta revisa el código o notebooks para ver instrucciones específicas.

Notas
------------------------------------------------------------

- La carpeta .history/ está ignorada en Git y solo es usada por VS Code para mantener historial de cambios.
- Algunos datasets grandes no están incluidos en el repositorio.
  Revisa cada carpeta y su README interno para instrucciones de descarga.
