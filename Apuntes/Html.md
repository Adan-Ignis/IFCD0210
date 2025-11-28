- Puede crearse el cuerpo con solamente pulsar "!" y luego "Switch" (Tabulador)

- Puede ponerse una etiqueta que se repite varias veces (una detra de otra) a la vez
    Se escribe la etiqueta y sin espacios se pone "*n", sustituyendo la "n" por el numero de veces que se necesita repetir esa etiqueta

- Titulos/Encabezados
    etiqueta <hn>, sustituyendo la "n" por un numero que va desde el 1 hasta el 6, llendo de más a menos importante

- Parrafos
    etiqueta <p>

    Nota: Es una mala practica utilizar la etiqueta para crear espacio entre parrafos. Para ello se debe usar la etiqueta <br> para un salto de linea

- Negrita
    etiqueta <br>

    Nota: No sirve para indicar que tiene gran importancia, para ello es necesario usar <strong>

- Cursiva (Italic o Italica en español)
    etiqueta <i>

    Nota: No sirve para hacer enfasis (que tiene importancia), para decir que es importante se utiliza la etiqueta <em>

- Tabular un parrafo
    etiqueta <blockquote>

    Nota: No necesita usarse la etiqueta <p> porque hace de contenedor

- Etiqueta de autocierre
    La etiqueta "funciona" como etiqueta de apertura y cierre

    Nota: No necesita usar "/" al principio, y si se pone debe ponerse al final de la etiqueta

- Enlaces (url)
    etiqueta <a href="">

        Nota: Es una mala practica utilizar ruta absoluta, lo correcto es usar ruta relativa

        Es una mala practica utilizar la "url" cuando se revisa una pagina web desde el ordenador de desarrollo, pues la IP hace referencia al propio equipo, porque buscan la información en el propio ordenador

- Enlaces (url) - Ruta interna
    Dentro de las dobles comillas, se pone "#" y unido el nombre del ID que tiene la etiqueta que da comienzo a la sección de la pagina web. Solamente sirve para moverse por la propia pagina web y no para cambiar de dirección (url)

    Ejemplo: Wikipedia hace esto con los indices

- Imagen
    Etiqueta <img>

    Atributos:
        src - Indica donde esta la imagen
        alt - Cuando la imagen no aparece aparecera lo que hay en alt, tambien los lectores de paginas para ciegos leeran lo que hay en alt
            alt - Texto descriptivo para cuando la imagen no aparece
            title -  
            figcaption - Texto visible debajo de la imagen, independientemente si la imagen se ve o no
        width - Marca el numero de pixeles que tiene a lo ancho
        height - Marca el numero de pixeles que tiene a lo alto

        loading - "eager" carga las imagenes de todas de golpe, mientras que "lazy" carga progresivamente los datos

        Nota: Si se pone solamente el "width" o el "height" el otro se calculara automaticamente para coincidir con la relacíon de aspecto de la imagen real (sin reescalado)