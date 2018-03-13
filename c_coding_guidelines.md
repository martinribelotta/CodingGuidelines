# Guía de estilo para lenguaje C
Esta guía pretenden condensar lineamientos generales para la programación en C dentro del proyecto CIAA.
## Estilo de código
El estilo de código base se sugiere que sea 'Java'.
 - En `astyle` el parámetro es `--style=java`
 - En Eclipse el template de codigo se llama de igual manera: `Java`
En otros IDE puede variar, pero siempre esta relacionado al estilo de llaves java, es decir, *attached braces*

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

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE0MjEzNDE2MDJdfQ==
-->