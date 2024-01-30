# Cadena o Strings
Una cadena es una secuencia de caracteres, es decir, una cadena es un array de caracteres. En Java, las cadenas son inmutables, es decir, no podemos modificar una cadena, si queremos modificar una cadena, tendremos que crear una nueva cadena.

# StringBuilder
StringBuilder es una clase que nos permite crear cadenas de forma mutable, es decir, podemos modificarlas. Para crear un StringBuilder, podemos utilizar el constructor StringBuilder() o StringBuilder(cadena).

        StringBuilder sb = new StringBuilder();
        StringBuilder sb2 = new StringBuilder("Hola mundo");
        sb.append("Hola mundo");
        String mensaje = sb2.toString();
