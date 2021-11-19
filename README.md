
** 

` `**MEDICIÓN, ESTIMACIÓN Y PLANEACIÓN:**

` `**CALCULATE.IO** 
**



**Elaborado por:**

[LAURA TATIANA RAMIREZ RODRIGUEZ](mailto:ltramirezr@correo.udistrital.edu.co)**20182020098**

[JUAN CAMILO CESPEDES ROMERO](mailto:jccespedesr@correo.udistrital.edu.co)**20182020065**

**JACKSON LUNA BONILLA 20182020084**


**Fundamentos de Ingeniería de Software**


**Presentado a:**

**Alejandro Daza Corredor**






**Noviembre de 2021**  

**Resumen**

Se planea desarrollar un software capaz de realizar operaciones básicas con números enteros, hexadecimales, octales y binarios.  Mediante la metodología SCRUM se definen los roles, se establecen los requerimientos funcionales y no funcionales, finalmente mediante el método COSMIC se enuncian los costos y tiempo necesarios para el desarrollo de la aplicación.






















# **Justificación**


Conforme pasa el tiempo la tecnología se va ganando una importancia cada vez más notoria en nuestras vidas  facilitando de una manera nuestras tareas ya sean simples o complejas en las diferentes áreas de la sociedad, avances como estos los vemos cuando ya no tenemos necesidad de alquilar una película en un negocio local, por que fueron reemplazados por los servicios de streaming, o cuando nos evitamos las filas para pagar un recibo en un establecimiento, solamente desde la comodidad de nuestra casa en un computador, tablet o celular.

En el tiempo que estamos pasando actualmente a nivel mundial, la tecnología a ayudado mucho en nuestras vidas ya que nos ha mostrado que aunque no podamos tener un contacto físico, si lo podemos hacer por medios virtuales, y a pesar de que no es igual si nos permite tener interacción personal y laboralmente; personal porque algunas personas ya venían utilizando medios virtuales para hacer compras, pagos de servicios públicos, pagos de créditos, entre otros, ahora con esta nueva realidad lo hacen un mayor número de personas porque se ha demostrado que es seguro hacer este tipo de transacciones virtualmente y también además nos a permitido tener contacto con nuestras familias sin importar el sitio donde estemos viviendo. Laboralmente porque igual que en lo personal en algunas empresas ya se venía utilizando las videoconferencias para realizar sus reuniones, un gran número de empresas han optado por esta opción y esto ahorra en recursos de tiempo y dinero en desplazamientos que en algunas ocasiones pueden llegar a ser innecesarios, así mismo se amplió mucho el campo del teletrabajo y esto llevado de una buena manera ayuda mucho al rendimiento laboral de una persona ya que lo puede realizar desde la comodidad de su casa sin que esto afecte sino que por el contrario mejore su potencial laboral.

Es por esto que por medio de este trabajo buscamos, mediante la metodología SCRUM realizar de manera eficiente un sistema de información que permita administrar los procesos de una panadería virtual, brindando soluciones a las necesidades presentadas por el cliente, en la agilización de las ventas, control de inventarios, egresos e ingresos.

Gracias a la implementación de esta metodología se podrán ver los avances de manera incremental en el desarrollo de la solución a entregar a los clientes finales, lo cual nos brinda la flexibilidad de poder realizar ajustes o mejoras al proceso con el avance de los diferentes Sprints.






## **Objetivos del proyecto**

El propósito de este proyecto es el de poder dar solución a la necesidad de una herramienta que realice operaciones matemáticas simples, implementando la posibilidad de que se puedan realizar estas mismas en varios sistemas numéricos. Esto se pretende lograr mediante una aplicación para la empresa ‘Distritalinos.co’. Esta aplicación tendrá despliegue de forma *standalone* desde el equipo del cliente o será web de acuerdo a la elección del product owner. La aplicación se encargará de realizar operaciones tales como cambio y selección de sistema numérico, suma, multiplicación, resta, división, potenciación, logaritmo, entre otras.

` `**Roles**

- **Cliente** 
- **Product Owner** 
- **Scrum Master**
- **Equipo de desarrollo**

**Metodología de trabajo**



**Requerimientos funcionales**

|**FORMULARIO DE ESPECIFICACIÓN DE REQUERIMIENTOS**|
| :-: |
|**IDENTIFICADOR:**|**NOMBRE:**|
| |` `Operaciones bàsicas de nùmeros|
|<p>**GRADO DE NECESIDAD**</p><p>**(NECESARIO / DESEABLE)**</p>|<p>**REQUERIMIENTO QUE LO**</p><p>**UTILIZA O ESPECIALIZA**</p>|
|Necesario||
|<p>**PRIORIDAD DE DESARROLLO**</p><p>**(A,M,B)**</p>|**DOCUMENTOS DE VISUALIZACIÓN ASOCIADOS**|
|A||
|**ENTRADA:**|**SALIDA:**|
|Nùmero 1 y nùmero 2|Resultado (operaciòn escogida de nùmero 1 con nùmero 2)|
|**PROCESO**|
|<p>**Descripción:**Se ingresarà el primer número digitalizado por el usuario en la caja de texto guardándolo en una variable al presionar el botón correspondiente a la operaciòn que desea realizar (+,-,/,\*,^,log) Se obtendrá el segundo número digitalizado por el usuario en la caja de texto guardándolo en una segunda variable y realizará la operaciòn guardando el resultado en una tercera variable.Mostrará la operación completa en la parte superior y el resultado en la caja de texto al presionar el botón =.</p><p></p>|
||
|**Precondición:**Se debe disponer de dos valores a los cuales se desee aplicar la la operación escogida por el usuario.|
||
|**Poscondición:**Se realizará la operación con los valores ingresados.|
||
|<p>**MANEJO DE SITUACIONES ANORMALES:**</p><p>El ingreso de caràcteres que no cumplen con el formato para digitalizar un valor que se vaya a operar, en este caso se mostrará un aviso de error y se pedirá el ingreso del dato de forma correcta nuevamente.</p>|
||
||
|<p>**CRITERIOS DE ACEPTACIÓN:**</p><p>Los datos se ingresan de manera correcta y se escoge una operación para realizar entre dos números.</p>|
||
||







|**FORMULARIO DE ESPECIFICACIÓN DE REQUERIMIENTOS**|
| :-: |
|**IDENTIFICADOR:**|**NOMBRE:**|
| |` `INGRESAR NÚMEROS|
|<p>**GRADO DE NECESIDAD**</p><p>**(NECESARIO / DESEABLE)**</p>|<p>**REQUERIMIENTO QUE LO**</p><p>**UTILIZA O ESPECIALIZA**</p>|
|NECESARIO|Interfaz |
|<p>**PRIORIDAD DE DESARROLLO**</p><p>**(A,M,B)**</p>|**DOCUMENTOS DE VISUALIZACIÓN ASOCIADOS**|
|ALTO||
|**ENTRADA:**|**SALIDA:**|
|Número|Número|
|**PROCESO**|
|<p>**Descripción:** El software por medio de botones y lectura de teclado es capaz de </p><p>almacenar y mostrar en interfaz los datos ingresados, tanto operaciones como datos para cálculo.</p>|
||
|**Precondición:** Se debe disponer de los mecanismos de entrada sean botones o lectura del teclado.|
||
|**Poscondición:** Los números deben permanecer almacenados y visibles el tiempo deseado. |
||
|**MANEJO DE SITUACIONES ANORMALES:**|
||
||
|**CRITERIOS DE ACEPTACIÓN:** Los datos deben ser visibles y fieles en todo momento a los datos ingresados por el usuario.|
||
||



|**FORMULARIO DE ESPECIFICACIÓN DE REQUERIMIENTOS**|
| :-: |
|**IDENTIFICADOR:**|**NOMBRE:**|
| |` `Cambio de Base|
|<p>**GRADO DE NECESIDAD**</p><p>**(NECESARIO / DESEABLE)**</p>|<p>**REQUERIMIENTO QUE LO**</p><p>**UTILIZA O ESPECIALIZA**</p>|
|NECESARIO|Operaciones básicas de números|
|<p>**PRIORIDAD DE DESARROLLO**</p><p>**(A,M,B)**</p>|**DOCUMENTOS DE VISUALIZACIÓN ASOCIADOS**|
|ALTO||
|**ENTRADA:**|**SALIDA:**|
|Número, base inicial y base final|Número en base final|
|**PROCESO**|
|**Descripción:** Se recibe el número y su correspondiente base, así mismo la base a la cual se desea transformar, para luego sea retornada en la base deseada.|
||
|**Precondición:** Se debe disponer de los mecanismos de entrada, sean botones o lectura del teclado y del programa que haga el cambio de base.|
||
|**Poscondición:**El dato resultante y el dato inicial deben permanecer guardados y visibles el tiempo deseado.|
||
|**MANEJO DE SITUACIONES ANORMALES:**|
||
||
|**CRITERIOS DE ACEPTACIÓN:** El valor inicial debe ser equivalente al resultado obtenido con cambio de base.|
||
||

` 	`**Requerimientos no funcionales**

El sistema debe poseer interfaces gráficas bien formadas en las cuales se pueda apreciar de forma clara la información que se presenta de cada producto.

●  	La interfaz gráfica debe ser muy sencilla en su navegación para el usuario, debe especificar de forma clara los pasos a seguir.

●  	Toda funcionalidad del sistema y operación lógica debe responder al usuario en un tiempo máximo de 5 segundos.

●  	El sistema debe estar con fuentes en español para proporcionar mensajes de error que sean informativos y orientados al usuario final.

●  	El sistema debe asegurar que los datos estén protegidos del acceso no autorizado.

●  	El desarrollo de la app deberá procurar el cumplimiento de los principios de alta cohesión y bajo acoplamiento, así como los principios SOLID. Con el fin de prolongar y facilitar la mantenibilidad de la app, y procurar la futura implementación de nuevas características.





**Medición y estimación**

El tamaño de un software es la principal variable necesaria para determinar el esfuerzo de desarrollo que deberá invertirse para implementarlo. La medición y estimación de software utilizando COSMIC, es un método de segunda generación que determina el tamaño del software a partir del número de interacciones entre los componentes de los requerimientos funcionales.

Estandarizado bajo la ISO 19761, se eligió el método COSMIC, dado que puede aplicarse a diversos tipos de software, incluyendo aplicaciones de negocios, sistemas de información gerencial, software en tiempo real, infraestructura, e inclusive software científico y de ingeniería.

Tiene la ventaja que no establece límites arbitrarios al tamaño funcional, por lo cual pueden medirse componentes de software independientemente de si son muy grandes o pequeños. Adicionalmente, el análisis para la medición está basado en el desglose funcional de los componentes de software, por lo que está alineado con las prácticas de Ingeniería de software.

- Asignación de puntos de función cosmic:

Asignamos un punto de función COSMIC por cada operación posible de la siguiente forma:

- Determinación del costo por unidad de medida:

Determinaremos el costo relacionado a desarrollar cada punto de función mediante la siguiente fórmula:

Costo por punto de función =Costo mes de trabajoPuntos de función del mes

Una vez que contamos con la medición del tamaño de la aplicación y el costo por unidad de medida, determinaremos el costo del proyecto de manera general usando la siguiente fórmula:

*Costo de un proyecto de software =Tamaño del software ⋅Costo por punto de función* 


- *Entrada: Ingresar Datos*
- *Entrada: Retroceder*
- *Lectura: Ver historial*
- *Lectura: Ver resultado*
- *Entrada: Identificar datos*
- *Escritura: Transformar los datos*

Ya con los puntos de función establecidos y conociendo que el costo del equipo de trabajo por persona es de:

4’000.000 COP X 3 (personas)

y que el equipo es capaz de realizar 10 puntos de función mensual entonces se tiene que:

Costo por punto de función =Costo mes de trabajoPuntos de función del mes

Costo por punto de función =4'000.000 X 310

Costo por punto de función =1'200.000 COP

Para la estimación de costo de desarrollar el proyecto se puede utilizar la siguiente fórmula:

Costo de un proyecto de software =Tamaño de software X Costo por punto de funcion

Costo de un proyecto de software =6 x (1'200.000)

Costo de un proyecto de software =7'200.000 COP

Para la estimación del tiempo necesario para desarrollar el proyecto se puede utilizar la siguiente fórmula:

Tiempo necesario =Puntos de función del proyecto Puntos de función del equipo de trabajo al mes

Tiempo necesario =6 10

Tiempo necesario =0.6 MESES


