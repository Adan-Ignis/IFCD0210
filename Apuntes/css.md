Como aplicar un CSS a un archivo html
    Hay tres maneras de hacerlo:

        1 - Definir los elementos del CSS dentro de la propia etiqueta, y se aplica solamente a esa etiqueta

        2 - Definir los elementos del CSS dentro del head del html, y se aplica a cada elemento del html

        3 - Poner un enlace del archivo CSS en el archivo html, y se aplica a cada html que lo "implemente"

    Nota: Hay una jerarquia a la hora de aplicarse el CSS, siguiendo las siguientes reglas:

        1 - Cercania, se aplicara el más cercano, teniendo el siguiente orden (de más cercano a más lejano):

            1 - CSS dentro de la propia etiqueta
            2 - CSS dentro del head del html
            3 - Archivo CSS independiente del html

        2 - Lo ultimo se aplicara.

            Si dentro del CSS se configura el mismo atributo, se aplicara el ultimo en aparecer.

        3 - El ultimo archivo CSS se aplicara

            Si un html se le implementa varios archivos CSS se le aplicara el ultimo que se implemento en el html

Aplicar estilo por etiqueta
    Se pone el nombre de la etiqueta y luego se pone "{}" dentro de estas se pone los atributos que se quiere aplicar al html

Aplicar estilo por id
    Se pone "#" y luego sin espacios se pone el nombre del id

    Nota: Solamente se puede tener un solo id en cada pagina y no lo puede compartir otra etiqueta aunque sea la misma

Aplicar estilo por class
    Se pone lo que hay dentro de class y luego dentro de "{}" se aplicara a todas las etiquetas que tenga esa clase

Aplicar estilo en general
    se pone "*{}" y todo lo que hay dentro de "{}" se aplicara a todo lo que hay en el html sin excepciones de ningún tipo

    Nota: Se le conoce como "selector universal"