# DATA4 Internship Front-end ![alt data4](https://media.licdn.com/media/p/6/005/06f/0e0/350be57.png)
## *Departamento de Data Driven Web Platforms*

DATA4 convierte datos en información accionable por medio de plataformas de recolección, processamiento, análisis y visualización de información, con principal enfoque en periodismo de datos, marketing científico y gobernanza.

El departamento de desarrollo de front-end está encargado de elborar plataformas y visualizaciones usando principalmente HTML5, CSS3, JQuery, AngularJS, D3.js. ¿Te interesa formar parte de DATA4? 

### Requerimientos
* Experiencia usando GIT
* Experiencia en Web Development: HTML5, CSS3 (Bootstrap, Foundation)
* Javascript (JQuery, AngularJS) y D3.js
* Desarrollo ágil y actualizaciones constantes
* Inglés

### Responsabilidades
* Construir y mantener sitios mediáticos de alto tráfico en Internet.
* Coordinación de proyectos, clientes, staff interno y desarrolladores externos.
* Planear, estimar, desarrollar y realizar actualizaciones constantes (GIT) a las plataformas en curso.
* Entregar código probado, funcional, comentado y fácil de interpretar al término de cada semana
* Participar en revisiones internas de código.
* Brindar soporte en las operaciones de las plataformas y responder a problemas de rendimiento. 

Si te interesa lo que realizamos en DATA4 y quieres formar parte, te invitamos a realizar la siguienre prueba para ser candidato a una entrevista personal. 

##Prueba D3.js - Índice de desarrollo humano

Desplegar una gráfica de barras en la que se muestran los valores del Índice de Desarrollo Humano de los 32 estados de la República Mexicana.

En la parte superior se ubican 3 dropdowns que permiten:
1. seleccionar un estado
2. seleccionar un año
3. ordenar los datos (alfabéticamente | ascendente | descendente)

**Datos**
Generar aleatoriamente los datos para las gráficas
1. Elegir un rango aleatorio de años
2. Dar a cada estado un valor aleatorio al IDH entre 0 y 1 (usar decimales)

**Gráfica**
Encapsular la lógica para dibujar la gráfica en una directiva de Angular.js que haga uso de los siguientes atributos:
1. data: un Arreglo de objetos con los datos con los que se pintará la gráfica
2. selected-state: Estado seleccionado -> destacar la barra de este estado con un color distinto
3. sort: forma de ordenar los datos
4. year: año que se quiere visualizar

**UX**
Cuando el ancho de la pantalla sea mayor a 480px, las barras deben ser verticales y los rótulos deben mostrar el nombre completo del estado; mientras que cuando sea menor o igual a 480px, las barras deben ser horizontales y los rótulos deben mostrar la abreviatura del estado.

Hacer la interfaz responsiva utilizando bootstrap.

La gráfica debe redibujarse cuando cambie el estado seleccionado, el año o la forma de ordenamiento, sin necesidad de botones adicionales.

**Plus**
1. Usar un generador de Yeoman como generator-gulp-angular [https://github.com/Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) para darle estructura al proyecto
2. Seguir la guía de estilo de AngularJS de John Papa, en particular el apartado sobre directivas [https://github.com/johnpapa/angular-styleguide#style-y075](https://github.com/johnpapa/angular-styleguide#style-y075). 
3. Configurar la directiva para que se utilice como elemento.
4. Comentar y explicar el código.
5. Instalar dependencias usando bower.

**Entrega**
Compartir el repositorio de Git en el que esté el código y si es posible, subir el proyecto usando un PaaS como Heroku u OpenShift.

**Mockup de la gráfica**
![alt mockup](assets/pruebaD3.jpg)





