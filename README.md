![](https://www.uao.edu.co/wp-content/uploads/2022/06/Logo-nuevo-acreditaci%C3%B3n.png)

### Descripción de la problemática

Al trabajar con conjuntos de datos, la detección y manejo de datos faltantes o nulos en las columnas es una preocupación importante. Es particularmente relevante en áreas como la fecha de nacimiento, la edad, el género, el correo electrónico y el teléfono, entre otras, donde la integridad y la precisión de los datos son esenciales para un análisis preciso y decisiones informadas.

Para abordar este problema de manera efectiva, es necesario implementar técnicas adecuadas de limpieza, validación y manejo de datos faltantes. Esto implica identificar registros con datos ausentes o nulos, determinar si estos registros son esenciales para el análisis o si se pueden eliminar, atribuir valores ausentes basándose en información relevante o utilizar métodos de interpolación según el contexto del problema.

La duplicidad de datos y la presencia de tipos de datos incorrectos en algunas columnas son problemas comunes además de la detección de datos faltantes. Por ejemplo, puede haber duplicados en registros de clientes, transacciones u otros datos. También puede haber situaciones en las que un dato de tipo numérico se encuentra en un campo string que debería ser , como el campo de valor de la boleta.

Ante estas inconsistencias, se requiere un análisis completo de los datos, la identificación y corrección de registros duplicados, la validación y modificación de los tipos de datos para garantizar que coincidan con las características de cada columna. Esto se logra mediante procesos de limpieza de datos, transformación de tipos de datos y validación de integridad, que mejoran la calidad y confiabilidad de los análisis y resultados del conjunto de datos.

# Contenido del repositorio 
- Limpieza_de_datos.ipynb
- Manipulación_de_datos.ipynb
- README.md
- datos_limpios.csv
- vsBucaramanga.csv (datos originales)

# Detalles sobre la cantidad y naturaleza de los datos

NOMBRE EVENTO: Esta columna contiene nombres de eventos deportivos hasta conciertos o conferencias.

DOCUMENTO: Este campo representa el tipo de identificación, como números de documento de identidad o pasaporte.

NOMBRE PERSONA: Aquí se registran los nombres de las personas que asisten a los eventos. Puede haber duplicados si varias personas comparten el mismo nombre.

NOMBRE DE ZONA: Esta columna indica la ubicación, zona o llamada tambien tribuna en los estadios donde se relaizan los eventos o partidos de futbol, normalmente un estadio cuenta con 4 ( norte, sur, oriental, occidental).

TIPO BOLETA: Indica el tipo de boleta o entrada asociada al evento, existen 4 tipos de boletas: Venta, Cortesía, Recaudo empresarial, Servicio al cliente.

VALOR: Representa el valor monetario asociado a la boleta o entrada. Dependiendo del tipo de boleta, estos valores pueden variar ampliamente.

PIN: Esta columna esta relacionada con los códigos de acceso o identificación. Son valores únicos en esta columna para cada boleta o entrada.

FECHA INGRESO: Indica la fecha en que la persona ingresó al evento. Es importante para análisis temporales y de asistencia.

CORREO: Aquí se registran las direcciones de correo electrónico de las personas relacionadas con el evento. Cada dirección de correo debería ser única.

CELULAR: Contiene números de teléfono celular de las personas. Deberían ser valores únicos para cada persona registrada.

FECHA NACIMIENTO: Indica la fecha de nacimiento de las personas relacionadas con el evento. Es crucial para análisis demográficos y tendencias.

EDAD:  Calculada a partir de la fecha de nacimiento, representa la edad de las personas, es importante para analizar tendencias de rangos de edades.

GENERO: Indica el género de las personas, con categorías como masculino, femenino.

#  Conclusiones y cómo genera valor a una empresa para una empresa

El conjunto de datos proporcionado, que incluye información detallada sobre eventos, personas y detalles de boletas, puede generar un valor significativo para una empresa en varios sentidos. A continuación se presentan algunas conclusiones sobre las posibles formas en que este conjunto de datos podría generar valor:

1. Análisis de asistencia y participación: una empresa puede comprender mejor la popularidad de ciertos eventos al analizar la cantidad de personas que asisten a diferentes tipos de eventos. También puede ajustar su estrategia de marketing y promoción en consecuencia. Esto puede aumentar la asistencia y la participación en eventos futuros.

2.  Segmentación de clientes y personalización: la empresa puede segmentar su base de clientes para brindar experiencias más personalizadas y adaptadas a las necesidades y preferencias de cada grupo demográfico con datos como la edad, el género y las preferencias de los asistentes.

3. Optimización de precios y estrategias de ingresos: la empresa puede cambiar sus estrategias de precios y crear ofertas y paquetes que maximicen los ingresos sin reducir la participación al analizar los valores de las boletas y la distribución de precios.

4. Gestión eficiente de la logística y los recursos: la empresa puede optimizar la gestión de la logística y los recursos al analizar los datos de asistencia y las fechas de ingreso, asegurándose de que haya suficientes recursos y personal para cada evento y evitar costos innecesarios.

5. Mejorar la experiencia del cliente: Al comprender mejor las preferencias y comportamientos de los clientes, la empresa puede mejorar la experiencia del cliente en los eventos ofreciendo servicios y comodidades adicionales que agreguen valor y fidelicen a los asistentes.

6. Detección de fraude y duplicados: el análisis de datos puede ayudar a detectar casos de fraude, como boletas falsas o duplicadas, protegiendo la integridad del evento y los ingresos de la empresa.
