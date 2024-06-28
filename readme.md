# BOX MODEL

- Se le aplica a cualquier elemento de la web

1. Los elementos ne bloque tienen un ancho y alto
el box model solo se aplica a los elementos en bloque
2. Los elementos inline, sus anchos son segun su contenido 
- Etiqueta DISPLAY


- De manera interno
    1. CONTENT : contenido (Es la parte central de la caja donde se coloca el contenido real del elemento, como texto, imágenes, etc.)
    2. PADDING : Es el espacio entre el contenido y el borde de la caja. Se utiliza para crear espacio interno alrededor del contenido.
   <!-- elemento interno
   padding : 5px 10px 5px 5px
    -->
    3. BORDER : Rodea el padding (si existe) y el contenido. El borde puede tener un grosor, estilo y color específicos. 
    <!-- elemento interno 
    border : 
     -->
- De manera externa
    1. MARGIN : Es el espacio fuera del borde de la caja. Se utiliza para crear espacio entre la caja y otros elementos circundantes.
   <!-- elemento externo 
   margin : 
    -->

BOX SIZING : BORDER BOX

- SELECTOR UNIVERSAL *
  <!-- * {
     box-sizing: border-box;
    } 
    -->
    Para que el tamaño no se altere, es decir, que el border o padding, se añade internamente, es como una resta al total