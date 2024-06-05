# Predicción del Rendimiento y Clasificación del Tipo de Explosión Nuclear utilizando Machine Learning.

Este proyecto tiene como objetivo predecir el rendimiento superior de una explosión nuclear y clasificar el tipo de explosión nuclear utilizando técnicas de machine learning. Utilizamos un archivo de datos denominado "nuclear_explosions.csv", que contiene información detallada sobre diversas pruebas nucleares.

## Contenido del Archivo nuclear_explosions.csv

El archivo nuclear_explosions.csv incluye información detallada sobre pruebas nucleares, como:

| Variable              | Clase     | Descripción                                                                                                                                                                                                                     |
|-----------------------|-----------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| fecha larga            | fecha     | ymd fecha                                                                                                                                                                                                                       |
| año                   | dobles    | año de explosión                                                                                                                                                                                                                |
| id-no                 | dobles    | identificación única                                                                                                                                                                                                            |
| país                  | carácter  | País desplegando el dispositivo nuclear                                                                                                                                                                                         |
| región                | carácter  | Región donde se desplegó dispositivo nuclear                                                                                                                                                                                    |
| fuente                | carácter  | La fuente que reportó el suceso de explosión                                                                                                                                                                                        |
| latitud               | dobles    | Posición de latitud                                                                                                                                                                                                             |
| longitud              | dobles    | Posición de la Longitud                                                                                                                                                                                                         |
| magnitud de cuerpo    | dobles    | magnitud de la onda corporal de explosión (mb)                                                                                                                                                                                  |
| magnitud-superficie   | dobles    | La magnitud de la onda superficial de la explosión (Ms)                                                                                                                                                                         |
| profundidad           | dobles    | Profundidad en la detonación en Km (podría ser subterráneo o sobre el suelo) - tenga en cuenta que positivo = profundidad (por debajo del suelo), mientras que negativo = altura (por encima del suelo)                          |
| rendimiento inferior          | dobles    | Explosión arroja menor estimación en kilotones de TNT                                                                                                                                                                           |
| rendimiento superior           | dobles    | Explosión rinde estimación superior en kilotones de TNT                                                                                                                                                                         |
| Propósito             | carácter  | Finalidad de la detonación: COMBAT (bombas de la Segunda Guerra Mundial lanzadas sobre Japón), FMS (prueba soviética, fenómeno de estudio de la explosión nuclear), ME (Ejercicio militar), PNE (explosión nuclear de paz), SAM (prueba soviética, modo accidental/emergencia), SSE (pruebas francesas/estudios estadounidenses - control de la seguridad de las armas nucleares en caso de accidente), TRANSP (Fementarios de Transporte), WE (British, French, EE.UU., Evaluar los efectos de la detonación nuclear en varios objetivos), WR (programa de desarrollo de armas) |
| nombre                | carácter  | Nombre del evento o de la bomba                                                                                                                                                                                                 |
| Tipo                  | carácter  | tipo - método de despliegue -- ATMOSPH (Atmospheric), UG (subterráneo), BALLOON (caja de caos), AIRDROP (Aeroplano desplegado), ROCKET (cuenco desplegado), TOWER (desprotegido en la parte superior de la torre construida), WATERSURFACE (sobre la superficie de la masa de agua), BARGE (en barcaza), SURFACE (en superficie o en cráter poco superficial), UW (bajo agua), SHAFT (hoja vertical), TUNNEL/GALLERY (Tolbo horizontal) |

🌐 Consulte el origen del  archivo aquí: [Nuclear Explosions](https://github.com/rfordatascience/tidytuesday/tree/2e9bd5a67e09b14d01f616b00f7f7e0931515d24/data/2019/2019-08-20)

## Requisitos.
  Python 3.11.9
  Librerías:
    * pandas: Manipulación y análisis de datos.
    * numpy: Operaciones numéricas y manejo de arrays.
    * seaborn: Visualización de datos.
    * IPython.display: Mostrar archivos SVG y salidas visuales.
    * matplotlib.pyplot: Creación de gráficos y visualizaciones.
    * sklearn.preprocessing: Preprocesamiento de datos.
    * sklearn.model_selection: División de datos y búsqueda de hiperparámetros.
    * sklearn.linear_model: Modelos de regresión.
    * sklearn.svm: Máquinas de soporte vectorial.
    * sklearn.metrics: Evaluación de modelos.
    * sklearn.pipeline: Creación de pipelines.
    * sklearn.feature_selection: Selección de características.
    * sklearn.ensemble: Modelos de bosque aleatorio.

## contacto.
  > 🧑Bustamante Juárez Eduardo. 🔢 Matrícula: 10056926 📬eduardo.bustamantej@uaem.edu.mx
  > 🏫 Centro de Investigación en Ciencias (UAEM).
  > 🌐 [Datos almacenados en Carpeta Drive](https://drive.google.com/drive/folders/1ZwhPfvGgJbIhCbWhqReYbAZj4T_eAMTh?usp=sharing)
