# Preguntas CPU

1. Si tengo un reloj que sincroniza toda la operacion del _datapath_ y cada instruccion dura exactamente un ciclo de reloj. Como es posible que pueda leer de y escribir al mismo registro en una misma instruccion? Por ejemplo en MIPS: `add $t1, $t1, $t2`. Ver el _datapath_ de MIPS en el libro de Patterson y Hennessy (pagina 265).
2. Explicar el concepto de _pipelining_ en el contexto del _datapath_ de una CPU.
3. Armar una lista con los posibles integrados de la serie 7400 para construir la CPU de TOY-8.
4. Por que en el diagrama del _datapath_ de MIPS32 hay memorias de instrucciones y datos separadas?
5. Por que los elementos de memoria (circuitos secuenciales) suelen tener una señal de `write` pero no es necesario que tengan una para `read`.
6. Logisim: implementar la CPU de TOY-8.
7. Logisim: implementar la CPU de TOY-16.
8. Logisim: implementar la CPU de MIPS usando el libro de Patterson y Hennesy como referencia.
9.

## Notas

El libro de Patterson y Hennesy esta en las netbooks, buscarlo en la particion que corresponde al disco `D:` en Windows.
Las CPU de TOY-8 y TOY-16 estan sacadas del libro de Sedgewick (Computer Science) tambien en las netbooks.
