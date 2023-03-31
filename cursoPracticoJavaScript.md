Curso Práctico de JavaScript
#### ¿Qué palabra reservada usarías para crear una variable que pueda cambiar su valor en el futuro?
		 let
###### Razón: let permite declarar variables limitando su alcance (scope) al bloque, declaración, o expresión donde se está usando. A diferencia de la palabra clave var la cual define una variable global o local en una función sin importar el ámbito del bloque.
###### Vídeo: [Variables](https://platzi.com/clases/3271-javascript-practico/51005-variables/)
------------
#### ¿Cuál es la diferencia entre declarar e inicializar?
		 Declarar es indicarle a JavaScript que crearemos una variable con cierto nombre. Inicializar (o reinicializar) es asignarle un valor a esa variable.
###### Razón: Una variable se declara para indicarle al programa a partir de qué lugar empieza a existir, qué nombre tendrá y qué tipo de datos almacenará. La asignación de un valor inicial se llama inicialización.
###### Vídeo: [Variables](https://platzi.com/clases/3271-javascript-practico/51005-variables/)
------------
#### ¿Cuál es la diferencia entre parámetro y argumento?
		 Las funciones reciben parámetros cuando las creamos. Y les enviamos argumentos cuando las ejecutamos.
###### Razón: Un parámetro es una variable utilizada para recibir valores de entrada en una rutina, subrutina o método. Dichos valores, que serán enviados desde la rutina invocante, son llamados argumentos.
###### Vídeo: [Funciones](https://platzi.com/clases/3271-javascript-practico/51006-funciones/)
------------
#### ¿Cuál será el resultado de la siguiente operación: 123 + "456"?
		 123456
###### Razón: El simbolo de + en Javascript concatena, el 123 es de número enterio mientras que que 456 es un string por ende concatena.
###### Vídeo: [Variables](https://platzi.com/clases/3271-javascript-practico/51005-variables/)
------------
#### ¿Cuál será el resultado de la siguiente operación: "Juan David" + "Castro Gallego"?
		 Juan DavidCastro Gallego
###### Razón: El simbolo de + en Javascript concatena, el resultado sale junto debido a que al final de la primera cadena no tiene espacio.
###### Vídeo: [Variables](https://platzi.com/clases/3271-javascript-practico/51005-variables/)
------------
#### ¿Es posible crear variables a partir de otras variables?
		 Verdadero
###### Razón: Es posible debido a que las variables pueden asignarse a otras por ejemplo var1 = "Excelente"; var2= var1+" día";
###### Vídeo: [Variables](https://platzi.com/clases/3271-javascript-practico/51005-variables/)
------------
#### ¿Cuál método o propiedad de los arrays nos permite leer la cantidad de elementos de un array en JavaScript?
		 .length
###### Razón: La función length en Javascript se usa para devolver la longitud de un objeto. Y dado que la longitud es una propiedad de un objeto, se puede usar tanto en arrays como en strings.
###### Vídeo: [Arrays y objetos](https://platzi.com/clases/3271-javascript-practico/51009-arrays-y-objetos/)
------------
#### ¿Cuál es la diferencia principal entre arrays y objetos?
		 En los arrays cada elemento se puede diferenciar por su índice o posición. En los objetos cada elemento tiene su propio nombre clave.
###### Razón: A diferencia de un objeto literal, que contiene distintas propiedades bajo el comando clave: valor, un objeto array contiene una lista de elementos separados por comas. Mientras que los objetos literales se introducen con los símbolos de llaves { }, los objetos array lo hacen con corchetes [ ].
###### Vídeo: [Arrays y objetos](https://platzi.com/clases/3271-javascript-practico/51009-arrays-y-objetos/)
------------
#### ¿Cómo podemos convertir un objeto en un array?
		 Object.values(nombreObjeto) u Object.keys(nombreObjeto)
###### Razón: El método Object.values() devuelve un array con los valores correspondientes a las propiedades enumerables de un objeto. Las propiedades son devueltas en el mismo orden a como lo haría un bucle for...in (la única diferencia es que un bucle for-in también enumera las propiedades en la cadena de prototipo de un objeto). El método estático Object.keys() devuelve un arreglo de propiedades enumerables propias de un objeto dado.
###### Vídeo: [Arrays y objetos](https://platzi.com/clases/3271-javascript-practico/51009-arrays-y-objetos/)
------------
#### ¿Cuál de las siguientes formas NO FUNCIONA para ejecutar código JavaScript AUTOMÁTICAMENTE cada vez que abrimos un documento HTML?
		 Copiando y pegando manualmente el código en la consola del navegador cada vez que abrimos o recargamos una página.
###### Razón: La forma correcta es colocarlo con la etiqueta script antes del cierre de la etiqueta de body
###### Vídeo: [Cómo conectar JavaScript con HTML](https://platzi.com/clases/3271-javascript-practico/51011-como-conectar-javascript-con-html/)
------------
#### ¿Qué herramienta de JavaScript nos permite seleccionar elementos de HTML?
		 Todas las respuestas son correctas.
###### Razón: document.getElementById, devuelve una referencia al elemento por su ID. document.getElementsByClassName(), retorna un objecto similar a un array de los elementos hijos que tengan todos los nombres de clase indicados. document.querySelector(), devuelve el primer elemento del documento que coincida con el grupo especificado de selectores, los selectores son cadenas de caracteres que contiene uno o más selectores CSS separados por coma.
###### Vídeo: [Leyendo HTML desde JavaScript](https://platzi.com/clases/3271-javascript-practico/51012-leyendo-html-desde-javascript/)
------------
#### ¿Qué herramienta de JavaScript nos permite editar elementos de HTML?
		 innerHTML
###### Razón: La propiedad Element.innerHTML devuelve o establece la sintaxis HTML describiendo los descendientes del elemento. Al establecerse se reemplaza la sintaxis HTML del elemento por la nueva.
###### Vídeo: [Escribiendo HTML desde JavaScript](https://platzi.com/clases/3271-javascript-practico/51013-escribiendo-html-desde-javascript/)
------------
#### ¿Qué herramienta de JavaScript nos permite crear un elemento HTML de tipo img?
		 document.createElement('img')
###### Razón: el método Document.createElement() crea un elemento HTML especificado por su etiqueta.
###### Vídeo: [Escribiendo HTML desde JavaScript](https://platzi.com/clases/3271-javascript-practico/51013-escribiendo-html-desde-javascript/)
------------
#### ¿Para qué sirve el event.preventDefault?
		 Para evitar que los eventos ejecuten su acción por defecto (por ejemplo, recargar la página al completar un formulario).
###### Razón: Cancela el evento si este es cancelable, sin detener el resto del funcionamiento del evento, es decir, puede ser llamado de nuevo.
###### Vídeo: [Eventos en JavaScript: interactuando con usuarios](https://platzi.com/clases/3271-javascript-practico/51014-eventos-en-javascript-interactuando-con-usuarios/)
------------
#### Ya tienes en JavaScript una variable input1 que selecciona un input de tu HTML. ¿Cómo puedes leer el valor que escriban los usuarios en ese input?
		 Ambas respuestas son correctas.
###### Razón: getAttribute() devuelve el valor del atributo especificado en el elemento. Si el atributo especificado no existe, el valor retornado puede ser tanto null como "" (una cadena vacía). value devuelve la propiedad de valorReturn the value property:
###### Vídeo: [Leyendo HTML desde JavaScript](https://platzi.com/clases/3271-javascript-practico/51012-leyendo-html-desde-javascript/)