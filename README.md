# DATA4 Front-end Data Vis Developer![alt data4](https://media.licdn.com/media/p/6/005/06f/0e0/350be57.png)
## *Departamento de Data Driven Web Platforms*

[DATA4](http://data4.mx/) convierte datos en información accionable por medio de plataformas de recolección, procesamiento, análisis y visualización de información, con principal enfoque en periodismo de datos, marketing científico y gobernanza. 

El departamento de desarrollo front-end está encargado de elaborar plataformas y visualizaciones usando principalmente HTML5, CSS3, JQuery, AngularJS, D3.js, y actualmente está buscando candidatos para internship. 

### Requerimientos
* Experiencia usando GIT
* Experiencia en Web Development: HTML5, CSS3 (Bootstrap, Foundation)
* Javascript (JQuery, AngularJS) y D3.js
* Desarrollo ágil y actualizaciones constantes
* Inglés

### Responsabilidades
* Planear, estimar, desarrollar y realizar actualizaciones constantes (GIT) a las plataformas en curso.
* Entregar código probado, funcional, comentado y fácil de interpretar al término de cada semana
* Participar en revisiones internas de código.
* Brindar soporte en las operaciones de las plataformas y responder a problemas de rendimiento. 

Estas herramientas son utilizadas para realizar sistemas de gestión y visualización de datos trabajando desde la arquitectura de los datos hasta la construcción de excelentes UI y UX de las plataformas. En el equipo de trabajo creemos firmemente en la colaboración y el aprendizaje continuo con mucha apertura a la experimentación y el auto aprendizaje. Si te interesa lo que realizamos en DATA4 y quieres formar parte del equipo de trabajo, te invitamos a realizar la siguiente prueba para ser candidato a una entrevista personal. 

## Prueba D3.js - Índice de desarrollo humano

Desplegar una gráfica de barras en la que se muestran los valores del Índice de Desarrollo Humano de los 32 estados de la República Mexicana.

En la parte superior se ubican 3 dropdowns que permiten:

1. Seleccionar un estado. 
2. Seleccionar un año.
3. Ordenar los datos (alfabéticamente | ascendente | descendente).

### Datos
Generar aleatoriamente los datos para las gráficas cuando se refresque la página.

1. Elegir un rango aleatorio de años
2. Dar a cada estado un valor aleatorio al IDH entre `0` y `1` (usar decimales)

### Gráfica
Encapsular la lógica para dibujar la gráfica en una directiva de Angular.js que haga uso de los siguientes atributos:

1. data: Un arreglo de objetos con los datos con los que se pintará la gráfica
2. selected-state: Estado seleccionado -> destacar la barra de este estado con un color distinto
3. sort: Forma de ordenar los datos
4. year: Año que se quiere visualizar

### UX
Cuando el ancho de la pantalla sea mayor a `480px`, las barras deben ser verticales y los rótulos deben mostrar el nombre completo del estado; mientras que cuando sea menor o igual a `480px`, las barras deben ser horizontales y los rótulos deben mostrar la abreviatura del estado.

Hacer la interfaz responsiva utilizando Bootstrap.

La gráfica debe re-dibujarse cuando cambie el estado seleccionado, el año o la forma de ordenamiento, sin necesidad de botones adicionales.

### Plus
1. Usar un generador de Yeoman como generator-gulp-angular \([https://github.com/Swiip/generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular)\) para darle estructura al proyecto
2. Seguir la guía de estilo de AngularJS de John Papa, en particular el apartado sobre directivas \([https://github.com/johnpapa/angular-styleguide#style-y075](https://github.com/johnpapa/angular-styleguide#style-y075)\). 
3. Configurar la directiva para que se utilice como elemento.
4. Comentar y explicar el código.
5. Instalar dependencias usando bower.

### Entrega
Compartir el repositorio de GIT en el que esté el código y si es posible, subir el proyecto usando un PaaS como Heroku u OpenShift.

### Mockup de la gráfica
![alt mockup](assets/pruebaD3.jpg)





