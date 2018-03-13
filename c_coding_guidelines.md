# Guía de estilo para lenguaje C
Esta guía pretenden condensar lineamientos generales para la programación en C dentro del proyecto CIAA.
## Estilo de código
El estilo de código base se sugiere que sea **Kernigan & Ritchie**.
 - En `astyle` el parámetro es `--style=k&r`
 - En Eclipse el template de codigo se llama de igual manera: `Kernigan & Ritchie`
En otros IDE puede variar, pero siempre esta relacionado al estilo de llaves java, es decir, *attached braces*

El espaciado usado son tres `3` espacios, Esta desviacion del estandar es debido a que permiten 

A continuación se detalla el esquema general con ejemplos de que esta bien y que esta mal en el uso de llaves:
```cpp
int function() { // Bien
   if (cond) { // Bien
      while(cond)
      { // Mal
      }
   } else
      { // Mal
      for (int i=0; i<10; i++)
          { printf("%d\n", i); } // Mal
      }
}
```
Para una explicación precisa de los *bracket styles* refierase a [la documentacion de aspell](http://astyle.sourceforge.net/astyle.html#_Brace_Style_Options)


<!--stackedit_data:
eyJoaXN0b3J5IjpbMTQwMDM5OTA5N119
-->