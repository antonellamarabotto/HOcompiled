1. El "pre-processing" deberia copiar el codigo de todos los include en el codigo del calculator.c
El "make assembler" deberia traducir el codigo C a un codigo assembler.
El "make object" deberia traducir el codigo assembler a el codigo de la maquina (0 y 1).
El "make  executable" ejecuta el archivo, produce el link entre el codigo maquina y la implementacion en la interfaz de la computadora.
2. El pre-processing genero un archivo pp_c que agrego antes del calculator.c, el codigo de todos los include y los simbolos. 
4. La funcion main es una funcion valga la redundancia, con el descriptor "T", es una funcion global, se puede acceder desde afuera del programa.
La funcion add_numbers es igual.
La funcion printf es "U"(undefined), implica que esa funcion no esta definida, porque recien cuando se ejecuta se genera su direccion de memoria, hasta este momento no es relevante.
5. Se agrega el soname; el printf aun esta indefinido, se define en el momento de la ejecucion. El soname es el tag de a que tiene que llamar cuando se esta ejecutando.


