ESLINT:

Es una herramienta que analiza el código para encontrar e informar de problemas en el código javscript.

Descompiendo sus significado
- ES (ECMAScript) - especificación en la que javascript se liga.
- Lint - palabra en inglés que define "pelusas"  y linter es como "rollo adhesivo que limpia pelusas y suciedad"

ESLint utiliza un sistema de reglas que permiten definir que es y que no es posible dentro del código, mejorando la calidad el código. Permite evaluar el código con el objetivo de mejorarlo. No fuerza una regla sino uno mismo le indica que grupo de reglas forzar a través de su configuración.

----------------------------

PRETTIER:

Es un formateador de código. Tambien analiza nuestro código JavaScript. Pero no solo detecta problemas (como la longitud de una línea, o si una variable no se usa nunca); re-escribe nuestro código cada vez que guardamos un archivo, permitiéndonos ver y entender cuales son los problemas de nuestra aplicación.

Nos permite tener nuestro código consistente como buena práctica.
Es particularmente beneficioso cuando se trabaja en un proyecto con múltiples colaboradores. Definir un conjunto de configuraciones ayuda en la legibilidad y comprensión del código. Puede dedicarse más tiempo a resolver problemas técnicos difíciles en vez de luchar contra problemas resueltos como la sangría del código.

Prettier garantiza consistencia en el formato de su código y hace que el proceso sea automático.

----------------------------

.EDITORCONFIG:

Es un archivo de configuración en el que define de forma genérica o filtrando según la extensión del archivo, y que se reposita junto con el proyecto.

De esta forma, a cualquiera que trabaje sobre el proyecto, se le aplicará automáticamente la configuración sin alterar la propia de su editor. Tan solo tendremos que instalar una extensión si el editor que usamos no es uno de los que lo traen por defecto instalado. 

Ayuda a mantener la misma configuración de editor para todos los miembros del equipo.

Es darle un estandar a todos los editores. Y debe de estar en la raíz del proyecto.