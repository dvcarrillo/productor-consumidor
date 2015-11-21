# productor-consumidor
Ejemplos básicos de programación concurrente:
 - **productor-consumidor.cpp** incluye una hebra que produce datos y los almacena en un vector y otra hebra que los consume, con dos semáforos que controlan su ejecucuión.
 - **fumadores.cpp** se trata de un problema donde un estanquero reparte tres tipos de productos, y cada uno de ellos
 lo necesita un distinto consumidor, los cuales los consumen al ser expedidos. Por tanto, se trata de un programa
 con 4 hebras y 4 semáforos que controlan su ejecución. Contando la nueva función que muestra estadísticas, se
 trataría de 5 hebras y 4 semáforos
 - **fumadores-con-monitores.java** es el mismo problema que el anterior, pero en este caso resuelto usando monitores en Java, utilizando una implementación estilo *Hoare*.
