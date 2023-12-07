## Selectores simples:

1. Selector de etiqueta: Para cambiar la forma general de una etiqueta general, por ejemplo
		a{} - a siempre genera una linea debajo del texto, si quisiera removerlo en todo el trabajo, se podría quitar.
		
		h1{}
2. Selector de clase: Para realizar estilos en la web, en la mayoria de casos se recomienda selector de clase, ya que es el valor más bajo que te permite especificidad, en casos especiales se podría usar otro.
3. Selector de ID: No se recomienda usar para CSS, se prefiere que se usen para la programación con JAVASCRIPT.
4. Selector InLine: Solo se debe usar para JavaScript para aplicar estilos. En Javascript se aplica estilos InLine.

Otros:
5. Selector de descendencia
6. Selector de anhidados

## Selectores compuestos:

1. Selector descendiente: se utilizan para especificar selectores dentro de otro


2. Selector hijo directo: solo afectaría al hijo directo del selector inicial


3. Selector de hermano siguiente o adyacente: +, selecciona a la etiqueta que esta al mismo nivel y en la siguiente linea del hermano



4. Selector a hermanos siguientes o adyacentes: ~, aplica a todos los hermanos después (no necesita ser inmediato despues), no aplica a nietos.


5. Selector multiples etiquetas: seleccionar varios elementos a la vez



Explicar que son los selectores, y mencionar con ejemplos y definicion. Selectores Simpels y Selectores Compuestos
Subirlo a git hub pages. y pasar en enlace del repo
readme.md generar un resumen de lo trabajado




## BOX MODEL


1. Todos los elementos en la web son rectangulares
2. width = ancho, height = alto
3. display block


Colores de una caja

Interno

Azul - content box
verde - padding box
melon - border box

Externo
naranja - margin box (ya no tiene el background que se aplica a la caja) separa frente a otros elementos

box-sizing: border-box (vuelve que el width y height sean absolutos, el border, padding y contenido van dentro)

existe el margin negativo

Los margenes verticales colapsan, si el elemento superior tiene margin-botton= 2 rem, el elemento superior tiene margin-top=2rem, colapsan, no se suman, en caso uno sea mayor que otro, el mayor se respeta.



    Aplicar conceptos y ejemplo de box model

    Que es box mode, el uso particulara de selector universal, explicar las capas del box model tanto internas como externas com ejemplos. .

    Explicar el shorthand padding , y margin.

    En margin explicar que es margin negativo, colapsadao de margenes verticales y el centrado perfecto horizontal.
