# Referencias · Detector de Tarjetas

Documentación externa que se usó para entender el hardware, los protocolos y las
libertades del proyecto. No es una bibliografía decorativa: cada enlace apunta a
la fuente que explica una decisión concreta.

## Fuentes técnicas

| Fuente | Para qué se consultó |
|---|---|
| [Arduino UNO Q](https://docs.arduino.cc/hardware/uno-q/) | Hardware, Linux y microcontroller de la UNO Q. |
| [OpenCV 4.x](https://docs.opencv.org/4.x/) | Captura, filtros, DNN y utilidades de imagen. |
| [Python 3](https://docs.python.org/3/) | Lenguaje, librería estándar y venv. |

## Versiones de este repositorio

`detector-tarjetas-completo`

Cada carpeta puede tener dependencias y versiones distintas. Cuando el código
depende de una versión específica, esa versión está declarada en el README o en
el archivo de configuración de la carpeta, no en este documento.

## Criterio de preservación

- El código y los documentos se copiaron desde la carpeta original de trabajo.
- Se excluyeron `.git`, dependencias instaladas, compilados, registros y bases
  de datos locales.
- Se redactaron tokens, claves privadas y contraseñas detectadas en texto.
- Las plantillas `.example`, `.sample` y los valores de demostración se
  conservan porque documentan la configuración esperada.

## Limitaciones conocidas

Identificar qué placa hay frente a la cámara suele requerir un modelo entrenado, GPU o una conexión a la nube, y aun así falla con etiquetas nuevas que nadie entrenó.

La documentación de cada versión describe el alcance real. Si una función no
está implementada, se dice; si un hardware no fue probado, también.
