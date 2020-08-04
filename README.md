****PRODUCTO DE UNIDAD #2****

****PROBLEMA:****

<p>¿Cuáles son los nodos y parámetros de configuración necesarios para el desarrollo de una Interfaz Humano Máquina, a su vez ,cuál es el modo de lectura de puertos virtuales en Raspberry para la elaboración de una calculadora científica usando el paradigma de programación orientada a objetos?</p>

****OBJETIVO GENERAL:****

<p>Investigar los usos ,estructuras y parámetros de configuración de la tarjeta de desarrollo Raspberry Pi y los componentes disponibles en Node-Red para el diseño de Dashboard   mediante la abstracción  y análisis de información,para su desarrollo y aplicación en una Calculadora científica e interfaz HMI (Interfaz Humano Máquina) respectivamente </p>

****OBJETIVOS ESPECÍFICOS:****

<p><li>Identificar estudios recientes que contengan información acerca de Node-Red,y la configuración de pines GPIO de la Raspberry Pi, para de esta forma conocer el objeto a investigar, el modo de uso de cada una de ellas y  las distintas aplicaciones en las que se encuentran.</li> </p>
<p><li>Comprender el modo de configuración para el diseño de Dashboard, la programación orientada a objetos, y la lectura de los puertos virtuales de una Raspberry PI en el simulador online.</li></p>
<p><li>Desarrollar un ejemplo de una interfaz de Node-RED utilizando dashboard, a más de una calculadora científica en Python empleando los conceptos investigados con anterioridad. </li></p>


***ESTADO DEL ARTE***

**Sobre la enseñanza de Raspberry Pi para programas universitarios de pregrado**
<p>Septimiu Mischie</p>
<p>Facultad de Electrónica y Telecomunicaciones, Universidad Politécnica de</p> <p>Timisoara, Rumania.</p>

<p>El presente estudio propone algunos aspectos relacionados con la enseñanza de Raspberry Pi aplicado en un programa universitario de pregrado.En el que se consideran lecciones de laboratorio y proyectos de diploma. En primer lugar se presenta la teoría básica necesaria para la comprensión del sistema a desarrollar,temas como  el uso de GPIO ,entrada de salida de propósito general, el acceso remoto desde una PC o la grabación a través de dos tipos de cámara.Es así que al aplicar dichos temas al desarrollo del proyecto se encuentra que per a que se puede crear archivos ejecutables que contengan Comandos Linux, la solución más óptima para implementar un número considerable de tareas complicadas es emplear lenguajes de programación como Python o C.Inicialmente,ambos idiomas pueden implementar el mismas tareas Sin embargo,existen ciertas diferencias a considerarse como el hecho de que el sistema operativo Raspbian contiene soporte para Python por defecto.Para hacer uso de los pines GPIO lo único que debe hacerse es importar la biblioteca GPIO por la instrucción de importación RPi.GPIO como GPIO .Existen dos formas de seleccionar el pin números : La primera corresponde a la numeración BCM2835,y es seleccionado por el instrucción GPIO.setmode (GPIO.BCM) . La segunda opción corresponde a la de  números naturales (1-26) del conector GPIO, la instrucción será será GPIO.setmode (GPIO.BOARD) .En cambio en el lenguaje C la  posibilidad de acceder a GPIO se da mediante el uso de el paquete WiringPi. Para instalarlo, el siguiente Linux los comandos deben ejecutarse.Para inicializar el paquete WiringPi, la función cableado ASetup () debe ejecutarse.En la investigación se presenta las acciones más importantes que pueden ser ejecutadas en una aplicación que requiere acceder al GPIO en tanto Python como es el proyecto de diploma que  presenta la implementación de una web servidor en Raspberry Pi. Los siguientes recursos están conectados al Raspberry Pi 2 modelo B en este caso: un Logitech C270 Cámara web, un sensor de temperatura análogo junto con un análogo convertidor digital con interfaz SPI y cuatro leds. En conclusión este artículo ha presentado algunas aplicaciones básicas de Raspberry Pi, así como dos más avanzadas.En las cuales, los fundamentos consisten en el uso del GPIO, las cámaras o el acceso remoto por SSH El avanzado utiliza las instalaciones como el servidor web, transmisión en vivo o visión estéreo.</p></p>



<p>Fecha de la conferencia: 27-28 de octubre de 2016</p></p>
<p>Fecha de adición a IEEE Xplore : 12 de diciembre de 2016</p></p>

<p>Este artículo al igual que nuestro trabajo se centra principalmente en los pines GPIO que posee la Raspberry pi , siendo estos considerados como entradas y salidas de propósito general; por esta funcionalidad es que permiten el ingreso y salida  de datos y variables externas ya sea que estén conectados a otros dispositivos o en este caso como en el ejemplo implementado en nuestro estudio ; la calculadora científica que  da la opción al usuario a interactuar con la tarjeta de desarrollo a través de la selección de múltiples pines para ejecutar la operación requerida.</p>




***Construcción de un sistema de monitoreo en el hogar con Node-RED***

<p>Chien-Yu Lu,  Fei-Hsu Chen,  Wen-Chiung Hsu,  Yu-Qiang Yang,  y Te-Jen Su</p> 


<p>Este estudio se centra en el diseño y desarrollo de un sistema de monitoreo en el hogar el cual consta de una imagen simple y una interfaz que incorpora electrodomésticos, prevención de desastres e instalaciones de vigilancia.Además, se encuentra el entorno de desarrollo visual Node-RED para crear el sistema,y que  los usuarios pueden configurar los parámetros ambientales por sí mismos con su Interfaz de programación simple y gráfica.Para la personalización de  la interfaz de usuario se incluye una codificación mediante el programa Nodo-RED que incluye : la transmisión de datos, reconocimiento visual en la nube y base de datos.Para el desarrollo del proyecto es necesario el uso de  Node.js. que es una fuente abierta y entorno multiplataforma para JavaScript, que hace que el JavaScript sea aplicable a programación en el servidor final.Todo este proyecto se basa el entorno de desarrollo visual Node-RED en el flujo, en el que  los usuarios pueden escribir el programa a través de una combinación de varios nodos. Estas los nodos pueden ser equipos de hardware, interfaces de programación de aplicaciones web (API web) o servicios en la nube, y el entorno de codificación .El flujo se puede editar en el medio de la pantalla, usando el nodo en el panel izquierdo, y la información de todos los nodos se puede ver a la derecha del panel. La herramienta del tablero gráfico también se puede usar para controlar dispositivos y monitorear información de varios dispositivos dentro del mismo dominio.  El menú desplegable en el la parte superior de la interfaz de control web le permite ver la información meteorológica de los condados y ciudades, y debajo está el indicador de calidad del aire y el estado actual de la contaminación del aire.Luego, el sistema de base de datos organiza los datos del sensor y almacena los datos en la base de datos.sistema de gestión, para que uno pueda ver los datos y detectar condiciones anormales en el futuro El nodo MQTT se utiliza para conectar los nodos de función, para obtener diversos datos del sensor,para organizarlos y fusionarlos, y finalmente, para vincularlos y almacenados en el sistema de base de datos. Finalmente, el sistema de reconocimiento de imágenes se divide en tres bloques en la interfaz de control web:fotos de alarmas móviles, datos de alarmas móviles y resultados de reconocimiento de imágenes. Primero usa la cámara de cámara de desplazamiento y transmisión de imágenes del programa para mostrar la imagen de transmisión en la interfaz de control web. Luego, detecte si hay nuevos archivos en la foto de la alarma de desplazamiento carpeta y organice los resultados para que se muestran en la interfaz de control web.</p>


<p>Fecha de recibimiento: 25 de septiembre de 2019.</p>
<p>Fecha de  aceptación: 19 de febrero de 2020</p>


<p>Este estudio guarda relación con la investigación que desarrollamos puesto que al trabajar con Node-Red se implementa una dashboard que  a través de la modificación de los parámetros de configuración de ciertos nodos,mismos que permiten visualizar una Interfaz gráfica que consta de nodos de tipo gauge en el caso del estudio del estado del arte mientras que en el nuestro se visualiza distintos tipos de gráficos como: la  donut,lineal,barras por nombrar algunos.En ambos casos el usuario puede interactuar con dicho tablero a traves de nodos como el slider.Es así que se muestra que la interacción humano-máquina constituye un puntal en el ámbito tecnológico ya que permite el desarrollo de entornos más inteligentes como el ejemplo presentado del monitoreo de una casa.</p>

****MARCO TEÓRICO****

***Node-RED***
<p>Node-RED es una herramienta de programación para conectar dispositivos de hardware, API y servicios en línea de formas nuevas e interesantes.Proporciona un editor basado en navegador que facilita la conexión de flujos utilizando la amplia gama de nodos en la paleta que se pueden implementar en su tiempo de ejecución con un solo clic.
Además cuenta con un dashboard o tablero de instrumentos que permite crear y visualizar varios widgets para interactuar con los dispositivos del internet de las cosas.</p>

***Uso del panel de control Node-Red***
<p>El diseño de la pantalla de la interfaz de usuario se puede controlar en la parte izquierda del tablero, donde se pueden encontrar los siguientes nodos: </p>

![](https://github.com/kdpena2/PU_GUI__DASHBOARD_NODE-RED/blob/master/IMAGENES%20PU2/Imagen%201.png)


<p>Para que en un programa existan varias pestañas se debe llamar a los nodos en diferentes grupos, además para generar subdivisiones dentro de estos, se nombran en distintas etiquetas. Con esto se logra una mejor visualización.</p> 
<p>Cada nodo del tablero tiene tres configuraciones importantes las cuales son:</p>
<p><li>Group/ grupo: Aquí se va a contener el nodo dentro del dashboard, si se va a implementar distintos nodos para un mismo objetivo, lo mejor sería colocarlos en el mismo grupo.</li></p>
<p><li>Label/ Etiqueta: Se asigna el nombre que va a tener cada uno de los nodos al ser mostrados.</li></p>
<p><li>Tooltip/ Información sobre herramientas: Se escribe una indicación al usuario, esta aparecerá al acercar el cursor al componente.</li></p>
<p><li>Nombre : Nombre que aparecerá en el  trabajo de flujo.</li>
  
![](https://github.com/kdpena2/PU_GUI__DASHBOARD_NODE-RED/blob/master/IMAGENES%20PU2/Imagen%202.png)

<p>En la parte derecha de la interfaz, podemos encontrar la organización de los grupos y sus respectivas etiquetas, con esto se puede cambiar el orden y elegir a nuestro gusto el widget que queremos visualizar  primero.</p>

![](https://github.com/kdpena2/PU_GUI__DASHBOARD_NODE-RED/blob/master/IMAGENES%20PU2/Imagen%203.png)

***Nodos más importantes en la dashboard:***
 
<p><li>Button: Agrega un botón a la interfaz del usuario, el cual al ser presionado debe dar como resultado lo que se indique. Los datos que se van a devolver pueden ser de tipo string, number, boolean, JSON, buffer, timestamp, flow o global.</li></p>
<p><li>Gauge: Este nodo muestra un widget de tipo de indicador en el tablero. Formateará los números pasados ​​a través de msg.payload en un widget de estilo indicador. El medidor contiene diferentes sectores y la aguja se moverá en distintas direcciones según el rango y el valor pasado al widget a través de msg.payload.</li>
<p><li>Numeric: Agrega un widget de entrada numérico a la interfaz de usuario, aquí se puede escoger el rango de números que se desee.</li>
<p><li>Slider: Agrega un control deslizante manipulable a la interfaz de usuario.</li> 
<p><li>Switch: Agrega un interruptor a la interfaz del usuario. Este incluye dos botones en su configuración, los cuales van a retornar dos estados en caso de ser presionados. Pueden ser de tipo entero, string, boolean, y entre otros.</li>
<p><li>Dropdown: Agrega un cuadro desplegable a la interfaz del usuario.Se escribe un texto que indique lo que debe seleccionar entre las opciones. También es posible escoger si se puede responder una sola opción o todas. Se escoge el tipo de dato que se va a ingresar, puede ser de tipo number, string o boolean, se añade el número de opciones que se quiera y en label se ingresa la opción.</li>
<p><li>Colour picker: Agrega un selector de color al tablero.Entre sus formatos se puede escoger entre hx, hx8, hsl, hsv, rgb.</li>
<p><li>Chart:Este nodo agrega un gráfico al tablero. El gráfico utiliza valores enviados a través de msg.payload para su visualización</li>
 

***¿Qué es Raspberry Pi?***

<p>Es un ordenador del tamaño de una tarjeta de crédito de bajo coste y tamaño reducido, creada con el objetivo de estimular la enseñanza de la informática en las escuelas, aunque no empezó su comercialización hasta el año 2012.
Consta de una placa base sobre la que se monta un procesador, un chip gráfico y memoria RAM. Esta placa que soporta varios componentes necesarios en un ordenador común y es capaz de comportarse como tal.
 <p>Su concepto es el de un ordenador desnudo de todos los accesorios que se pueden eliminar sin que afecte al funcionamiento básico. 
**Los pines GPIO (General Purpose Input Output):** 
<p>General Purpose Input Output (GPIO) es un sistema de entrada y salida de propósito general, es decir, consta de una serie de pines o conexiones que se pueden usar como entradas o salidas para múltiples usos. Estos pines están incluidos en todos los modelos de Raspberry Pi aunque con diferencias.</p>
Estos pines son digitales, lo que significa que sólo pueden tener dos estados, apagado o encendido. Pueden tener una dirección para recibir o enviar corriente (entrada, salida respectivamente) y todo esto es totalmente controlable por lenguajes de programación como Python, JavaScript, node-RED y otros. Los pines trabajan con una tensión de 3,3 V y un consumo máximo de corriente de 16 mA. Esto significa que podemos suministrar energía de forma segura desde un solo pin GPIO a través de una resistencia y uno o dos LEDs. 
<p>Para controlar GPIO con Python, lo primero es importar una librería de código escrito previamente. El más común y difundido es el RPi.GPIO, utilizado para crear miles de proyectos desde los primeros días de la Raspberry Pi.</p>
<p>En cuanto a la nomenclatura de los pines GPIO, existen dos maneras de identificarlos; el método más simple es definitivamente el que se refiere a su ubicación física (BOARD). </p> <p>Empezando por la parte superior izquierda del GPIO, tenemos el pin físico 1 que proporciona alimentación 3v3. A la derecha de ese pin se encuentra el pin físico de 2 que proporciona 5v de potencia. El número de pines seguirá creciendo a medida que se desciende por las columnas. A la izquierda se encontrarán todos los pines con números impares y a la derecha los pares. </p>
<p>Existe otro método utilizado, y es la numeración de pines de Broadcom (BCM), el cual se refiere a los alfileres GPIO que están conectados directamente al SoC del Raspberry Pi. Básicamente son conexiones directas al cerebro de nuestra Pi para conectar sensores y
componentes para usar en nuestros diseños.  </p>

![](https://github.com/kdpena2/PU_GUI__DASHBOARD_NODE-RED/blob/master/IMAGENES%20PU2/Imagen%204.png)


**PROGRAMACIÓN ORIENTADA A OBJETOS**

<p>La programación orientada a objetos se define como un paradigma de la programación, una manera de programar específica, donde se organiza el código en unidades denominadas clases, de las cuales se crean objetos que se relacionan entre sí para conseguir los objetivos de las aplicaciones. </p>
<p>La programación orientada a objetos (POO) es una forma especial de programar, más cercana a cómo expresamos las cosas en la vida real que otros tipos de programación. </p>
<p>En este paradigma se tienen distintos elementos que se describen a continuación: </p>

![](https://github.com/kdpena2/PU_GUI__DASHBOARD_NODE-RED/blob/master/IMAGENES%20PU2/Imagen%205.png)


 ***Clases*** 
 
<p>Una clase es la descripción de un conjunto de objetos similares; consta de métodos y de datos que resumen las características comunes de dicho conjunto. En un lenguaje de programación orientada a objetos se pueden definir muchos objetos de la misma clase de la misma forma que, en la vida real, haríamos galletas (objeto) con el mismo molde (clase) solo que, para entenderlo mejor, cada galleta tendría igual forma pero es posible que tenga distinto sabor, textura, olor, color, etc. </p>
<p>Dicho de otro modo, una clase es la declaración de un tipo de objeto. Las clases son similares a los tipos abstractos de datos y equivalen a modelos que describen cómo se construyen ciertos tipos de objetos. Cada vez que se construye un objeto a partir de una clase estamos creando lo que se llama una instancia de esa clase.  </p>

***Objeto***

<p>Se trata de un ente abstracto usado en programación que permite separar los diferentes componentes de un programa, simplificando así su elaboración, depuración y posteriores mejoras. </p>
<p>Los objetos se integran, a diferencia de los métodos procedurales, tanto los procedimientos como las variables y datos referentes al objeto. </p>
<p>A los objetos se les otorga ciertas características en la vida real. Cada parte del programa que se desea realizar es tratado como objeto, siendo así estas partes independientes las unas de las otras.Los objetos se componen de 3 partes fundamentales: métodos, eventos y atributos. </p>

***Métodos***

<p>Son aquellas funciones que permiten efectuar el objeto y que nos rinden algún tipo de servicio durante el transcurso del programa. </p>
<p>Determinan a su vez como va a responder el objeto cuando recibe un mensaje. </p>

**Eventos**

<p>Son aquellas acciones mediante las cuales el objeto reconoce que se está interactuando con él. </p>
<p>De esta forma el objeto se activa y responde al evento según lo programado en su código. </p>

**Atributos**

<p>Características que aplican al objeto solo en el caso en que el sea visible en pantalla por el usuario; entonces sus atributos son el aspecto que refleja, tanto en color, tamaño, posición, si está o no habilitado. </p>

***Python*** 

<p>Python es un lenguaje de programación de alto nivel, interpretado y multipropósito, que en los últimos años ha tenido un auge considerable ya que constituye uno de los lenguajes más empleados en el desarrollo de software .Python puede ser utilizado en  diversas plataformas y sistemas operativos, entre los que se puede destacar los más populares, como Windows, Mac OS X y Linux . Este lenguaje nos permite trabajar en el paradigma de programación orientado a objetos ,siguiendo la estructura que se muestra en la imagen: </p> 

![](https://github.com/kdpena2/PU_GUI__DASHBOARD_NODE-RED/blob/master/IMAGENES%20PU2/Imagen%206.png)


****Librería Math*****

<p>La librería math es proveída por Python como parte de su "librería estándar" y ofrece funciones matemáticas para uso en el campo de los números reales. Algunas de las funciones ofrecidas son: </p>

*****Funciones numéricas*****

<p><li>math.ceil(x): Devuelve el entero más próximo mayor o igual que x.</li> </p>
<p><li>math.floor(x): Devuelve el entero más próximo menor o igual que x. </li></p>
<p><li>math.gcd(a, b): Devuelve el máximo común divisor ("greatest common divisor") <p>de los números a y b.</li> </p>
<p><li>math.isnan(x): Devuelve el booleano True si x es un NaN ("Not a Number").</li> </p>

***Funciones de potencia y logarítmicas***

<p><li>math.exp(x): Devuelve ex.</li> </p>
<p><li>math.log(x, [base]): Devuelve el logaritmo neperiano de x. Si se incluye el </p> <li>segundo argumento, devuelve el logaritmo de x en la base indicada. </p>
<p><li>math.log2(x): Devuelve el logaritmo en base 2 de x.</li> </p>
<p><li>math.log10(x): Devuelve el logaritmo en base 10 de x.</li> </p>
<p><li>math.pow(x, y): Devuelve xy. </li></p>
<p><li>math.sqrt(x): Devuelve la raíz cuadrada de x. </li></p>

***Funciones trigonométricas y de conversión de ángulos***

<p><li>math.cos(x): Devuelve el coseno de x. </li></p>
<p><li>math.sin(x): Devuelve el seno de x.</li> </p>
<p><li>math.tan(x): Devuelve la tangente de x.</li> </p>
<p><li>math.degrees(x): Convierte un ángulo de grados sexagesimales a radianes. </p>
<p><li>math.radians(x): Convierte un ángulo de radianes a grados sexagesimales.</li> </p>

***Constantes***

<p><li>math.pi: Numero pi.</li></p>
<p><li>math.e: Número e.</li></p>
<p><li>math.nan: Valor equivalente a "no es un número".</li></p>
<p>Para poder acceder y hacer uso de  esta librería, al iniciar el código debemos ingresar la siguiente línea:</p>
<p>import math</p>

![](https://github.com/kdpena2/PU_GUI__DASHBOARD_NODE-RED/blob/master/IMAGENES%20PU2/Imagen%207.png)

***SOFTWARE***

***Plataforma:***

<p>La plataforma Created.with code.uk, es una herramienta gratuita donde se permite escribir, ejecutar, depurar y compartir programas de Python en el navegador web.Su ventaja es que no se necesita descargar ni instalar ningún archivo, es así que los programas de Python no pueden acceder a los archivos o dañar la computadora, por lo que es una forma segura de aprender a crear con código.</p>

****DIAGRAMAS****

<p>Interfaz HMI (Interfaz Humano Máquina) </p>

![](https://github.com/kdpena2/PU_GUI__DASHBOARD_NODE-RED/blob/master/IMAGENES%20PU2/Imagen%208.png)


<p>Diagrama de flujo de la aplicación “Calculadora” en Raspberry Pi.</p>

![](https://github.com/kdpena2/PU_GUI__DASHBOARD_NODE-RED/blob/master/IMAGENES%20PU2/Imagen%209.png)

![](https://github.com/kdpena2/PU_GUI__DASHBOARD_NODE-RED/blob/master/IMAGENES%20PU2/Imagen%209.1.png)

![](https://github.com/kdpena2/PU_GUI__DASHBOARD_NODE-RED/blob/master/IMAGENES%20PU2/Imagen%209.2.png)

![](https://github.com/kdpena2/PU_GUI__DASHBOARD_NODE-RED/blob/master/IMAGENES%20PU2/Imagen%209.3.png)

![](https://github.com/kdpena2/PU_GUI__DASHBOARD_NODE-RED/blob/master/IMAGENES%20PU2/Imagen%209.4.png)

![](https://github.com/kdpena2/PU_GUI__DASHBOARD_NODE-RED/blob/master/IMAGENES%20PU2/Imagen%209.5.png)

![](https://github.com/kdpena2/PU_GUI__DASHBOARD_NODE-RED/blob/master/IMAGENES%20PU2/Imagen%209.6.png)

![](https://github.com/kdpena2/PU_GUI__DASHBOARD_NODE-RED/blob/master/IMAGENES%20PU2/Imagen%209.7.png)



****LISTA DE COMPONENTES****

<p>Estos son los recursos que se han utilizado a lo largo del desarrollo del trabajo de investigación.</p>

![](https://github.com/kdpena2/PU_GUI__DASHBOARD_NODE-RED/blob/master/IMAGENES%20PU2/Imagen%2010.png)


****MAPA DE VARIABLES****


![](https://github.com/kdpena2/PU_GUI__DASHBOARD_NODE-RED/blob/master/IMAGENES%20PU2/Imagen%2011.png)




****EXPLICACIÓN DE CÓDIGO FUENTE****

***Dashboard Node-RED***

***Etiqueta First:***

<p>En los botones 1,2,3 y 4 se muestran íconos que pueden ser presionados, estos tendrán su respectivo código y color asignado, es así que para mostrar el primer ícono se escribe fa-male, fa-female para el segundo, twitter para el tercero y fa-car en el cuarto. Al presionar cada uno de estos se mostrará un mensaje al usuario, el cual se logra conectándolos al nodo text.</p>


![](https://github.com/kdpena2/PU_GUI__DASHBOARD_NODE-RED/blob/master/IMAGENES%20PU2/Imagen%2012.png)


<p>A continuación se mostrará un gauge, el cual estará conectado a un slider para su manipulación,  una salida de texto que mostrará los valores en los que se encuentra y el nodo numeric el cual tiene una configuración de cinco en cinco para controlar al gráfico.</p>


![](https://github.com/kdpena2/PU_GUI__DASHBOARD_NODE-RED/blob/master/IMAGENES%20PU2/Imagen%2013.png)


<p>También en esta parte encontraremos los nodos dropdown y switch, en el dropdown se pueden escoger opciones dentro de una lista, en nuestro caso hemos seleccionado los tres tipos de datos que pueden mostrarse, los cuales son number, string y boolean. El uso del nodo switch se evidencia en el gráfico, este al ser presionado irá del 0 al 100%. </p>


![](https://github.com/kdpena2/PU_GUI__DASHBOARD_NODE-RED/blob/master/IMAGENES%20PU2/Imagen%2014.png)


***Etiqueta Second:***

<p>En este caso se visualizan tres  sliders que al ser manipulados por el usuario cada uno enviará datos a los gráficos de la tercera etiqueta.</p>


![](https://github.com/kdpena2/PU_GUI__DASHBOARD_NODE-RED/blob/master/IMAGENES%20PU2/Imagen%2015.png)


<p>Luego tenemos un gauge de tipo donut  conectado al tercer slider configurado con valores en un rango de :  0 como mínimo  y 100 como máximo ,por lo que tomará los valores correspondientes al movimiento que el usuario realice en el último slider.</p>



![](https://github.com/kdpena2/PU_GUI__DASHBOARD_NODE-RED/blob/master/IMAGENES%20PU2/Imagen%2016.png)

 
<p>En la parte inferior al gauge encontramos el nodo dropdown que agrega un cuadro desplegable al panel, y en donde hemos colocado datos de tipo number, los cuales manipulan al gauge anterior. El nodo colour picker agrega un selector de color al tablero configurado con un formato  hexa y de forma circular, este también manipulará al gráfico anterior en caso de que coincida el número hexadecimal con los valores en los que se encuentra el rango.</p>


![](https://github.com/kdpena2/PU_GUI__DASHBOARD_NODE-RED/blob/master/IMAGENES%20PU2/Imagen%2017.png)


***Etiqueta Third:***

<p>Esta tercera etiqueta es más bien un anexo a la segunda ya que los nodos chart de tipo :</p>
<p><li>Line chart(muestra valores de forma lineal )</li></p>
<p><li>Pie chart(gráfico en forma circular )</li>
<p><li>Bar chart (muestra valores a través de un gráfico de barras)</li>
<p><li>Bar chart(H)(muestra valores de igual forma que el anterior con la diferencia que lo hace de forma horizontal)</li>
<p>Están conectados a los deslizantes de la segunda etiqueta , dichos deslizantes permiten observar cómo los valores varían dependiendo de su manipulación en los gráficos .</p>
 
 
![](https://github.com/kdpena2/PU_GUI__DASHBOARD_NODE-RED/blob/master/IMAGENES%20PU2/Imagen%2018.png)

***Calculadora científica Raspberry y Python***

<p>   Utilizamos las librerias RPi.GPIO y math para poder manipular y visualizar las entradas GPIO y realizar operaciones tanto simples como complejas respectivamente. </p> 
<p> Usamos GPIO.input(x) == GPIO.HIGH: donde x viene a ser el Pin a manipular, únicamente utilizaremos 6  pins debido a la generación de menús y submenús. </p> 
 
![](https://github.com/kdpena2/PU_GUI__DASHBOARD_NODE-RED/blob/master/IMAGENES%20PU2/Imagen%2019.png)

<p> Para realizar los submenús utilizamos funciones en donde ingresamos texto que nos indique lo que se va realizar y a continuación las operaciones que permitan tener un valor de retorno.</p> 
 
![](https://github.com/kdpena2/PU_GUI__DASHBOARD_NODE-RED/blob/master/IMAGENES%20PU2/Imagen%2020.png)

<p> Utilizamos cada operación respectivamente con la librería math la cual nos simplificará el proceso. </p> 
 
**Funciones de potencia y logarítmicas**

<p><li>math.exp(x): Devuelve ex.</li></p>
<p><li>math.log(x, [base]): Devuelve el logaritmo neperiano de x. Si se incluye el segundo argumento, devuelve el logaritmo de x en la base indicada. </li></p>
<p><li>math.pow(x, y): Devuelve xy.</li></p>
<p><li>math.sqrt(x): Devuelve la raíz cuadrada de x. </li></p>

**Funciones trigonométricas y de conversión de ángulos**

<p><li>math.cos(x): Devuelve el coseno de x. </li></p>
<p><li>math.sin(x): Devuelve el seno de x.</li></p>
<p><li>math.tan(x): Devuelve la tangente de x.</li></p>
<p><li>math.degrees(x): Convierte un ángulo de grados sexagesimales a radianes. </li></p>
<p><li>math.radians(x): Convierte un ángulo de radianes a grados sexagesimales.</li></p>

<p> Llamamos a los resultados para poder mostrarlos y los aglomeramos dentro de un while, que tiene la funcionalidad de preguntar si deseamos realizar otra operación para permitirnos regresar al primer menú. </p> 

![](https://github.com/kdpena2/PU_GUI__DASHBOARD_NODE-RED/blob/master/IMAGENES%20PU2/Imagen%2021.png)

<p>El proceso se repite con cada método de nuestro programa.  </p> 
 
****DESCRIPCIÓN DE PRERREQUISITOS Y CONFIGURACIÓN****

![](https://github.com/kdpena2/PU_GUI__DASHBOARD_NODE-RED/blob/master/IMAGENES%20PU2/Imagen%2022.png)

****APORTACIONES****

<p><li>La principal aportación que tiene nuestro programa en el dashboard de node-RED, es que todos los nodos van a realizar una determinada función en la interfaz, es así que el nodo numeric con valores asignados en paso de cinco va a manipular al primer gauge, al igual que el switch que está configurado de 0 a 100 y el primer slider. A más de esto, el segundo gauge fue conectado por un dropdown con salida de tipo number que contiene valores establecidos, y un nodo colour picker con el cual también es posible manipular nodos que necesiten valores de ingreso, para una mejor visualización se lo conectó a un gráfico y este va cambiando de valores conforme al número hexadecimal de cada color. </li></p>
<p><li>Se implementó el uso del nodo range, el cual asigna un valor numérico a un rango diferente al de la entrada. Este nodo escalará linealmente el valor recibido. Por defecto, el resultado no está limitado al rango definido en el nodo. También el resultado nunca estará fuera del rango especificado. En su configuración de carga útil debe ser un número, en caso de no ser así será analizado y rechazado. En las salidas irá el valor asignado al nuevo rango.</li></p>
 
****CONCLUSIONES****

<p><li>Node-Red brinda una interfaz gráfica que se observa en pantalla como un dashboard , en el cual se podrá visualizar varias pestañas mediante una llamada a los nodos en diferentes grupos que a su vez se encuentra en subdivisiones creadas, al darnos esta posibilidad el usuario podrá interactuar con varias pestañas en un mismo tablero.</li></p>
<p><li>La implementación de una interfaz gráfica basada en flujos brinda un ambiente más amigable para los desarrolladores en el aprendizaje de las nuevas tecnologías. Se debe promover esta metodología que permite al usuario observar de forma más detallada la interacción que existe entre software y hardware.</li></p>
 
 
 
****RECOMENDACIONES****

<p><li>Es recomendable conocer las librerías existentes en el programa a usar a fin de evitar que se realicen funciones innecesarias , mismas que ya pueden existir dentro del lenguaje de programación ;en este caso python cuenta con la librería math que nos ofrece una variedad de funciones que pueden emplearse en la solución a problemas de índole matemático.</li></p>
<p><li> No olvidar las reglas sintácticas que tiene el lenguaje Python, ya que este se caracteriza por ser estricto en el caso de las indentaciones y las debidas puntuaciones. Conocer las palabras reservadas, los identificadores (los cuales determinan una variable, función, clase, módulo u objeto). Python también diferencia entre mayúsculas y minúsculas y no admite caracteres de puntuación como @, $ o %.</li></p>
- <p><li>Se recomienda inicializar la entrada de pin en alto debido a que de otra forma no será seleccionado.</li></p>
<p><li>En el caso del Dashboard de node-Red se recomienda conocer los nodos que lo contienen y cada uno de los parámetros de configuración de estos a fin de una mejor manipulación y resultados.</li></p>

****CRONOGRAMA****

![](https://github.com/kdpena2/PU_GUI__DASHBOARD_NODE-RED/blob/master/IMAGENES%20PU2/Imagen%2023.png)

****BIBLIOGRAFÍA****

<p><li>S. Mischie, "On teaching Raspberry Pi for undergraduate university programmes," 2016 12th IEEE International Symposium on Electronics and Telecommunications (ISETC), Timisoara, 2016, pp. 149-153, doi: 10.1109/ISETC.2016.7781079.</li></p>
<p><li>Lu, C. Y., Chen, F. H., Hsu, W. C., Yang, Y. Q., & Su, T. J. (2020). Constructing Home Monitoring System with Node-RED. Sensors and Materials, 32(5), 1701-1710.</li></p>
<p><li>OpenJS Foundation. (s.f.). Node-red. Obtenido de Node-red: https://nodered.org</li></p>
<p><li>OpenJS Foundation. (Julio de 2020). Node-RED. Obtenido de https://flows.nodered.org/node/node-red-dashboard</li></p>
<p><li>Sum, P. E. (2017, 26 diciembre). ¿Qué es GPIO? - Control de GPIO con Python en Raspberry Pi. https://www.programoergosum.com. https://www.programoergosum.com/cursos-online/raspberry-pi/238-control-de-gpio-con-python-en-raspberry-pi/que-es-gpio</li></p>
<p><li>Qué es la programacion orientada a objetos. (2019, 11 diciembre). Desarrollo Web. https://desarrolloweb.com/articulos/499.php</li></p>
<p><li>LA LIBRERÍA MATH. (s. f.). InteractiveChaos. https://www.interactivechaos.com/manual/tutorial-de-python/la-libreria-math</li></p>
<p><li>Challenger-Pérez, I., Díaz-Ricardo, Y., & Becerra-García, R. A. (2014). El lenguaje de programación Python. Ciencias Holguín, 20(2), 1-13.</li></p>
 
 
***ANEXOS:***

![](https://github.com/kdpena2/PU_GUI__DASHBOARD_NODE-RED/blob/master/IMAGENES%20PU2/Imagen%2024.png)

![](https://github.com/kdpena2/PU_GUI__DASHBOARD_NODE-RED/blob/master/IMAGENES%20PU2/Imagen%2025.png)

![](https://github.com/kdpena2/PU_GUI__DASHBOARD_NODE-RED/blob/master/IMAGENES%20PU2/Imagen%2026.png)
 







 















