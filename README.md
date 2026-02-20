# Mav_Depen_ValidExpre_Ofus

*5. Parte D*
Breve análisis escrito explicando:

¿Qué tanto se dificulta la lectura?
  La lectura sí se dificulta bastante en el código ofuscado. Esto se debe a que los nombres originales de las clases, métodos y variables fueron cambiados por letras simples como “a” o nombres muy genéricos como “paramChar1”. En el código original era más fácil entender qué hacía cada método solo por el nombre, pero en el ofuscado ya no se puede saber eso a simple vista y es necesario leer todo el bloque para comprenderlo.

¿Se pierde claridad estructural?
  No se pierde completamente la estructura del programa. Los ciclos for, las condiciones if y los retornos siguen estando en el mismo orden y cumplen la misma función. Sin embargo, aunque la estructura general se mantiene, sí se pierde claridad en cuanto a la intención del código, porque los nombres ya no ayudan a entender qué está pasando.

¿Sigue siendo posible entender la lógica?
  Sí, todavía es posible entender la lógica del programa, pero requiere más tiempo y análisis. Aunque los nombres fueron cambiados, las comparaciones y el flujo del algoritmo siguen visibles, por lo que una persona que revise el código con atención puede deducir que se trata de un validador de símbolos usando una pila.


*6. Parte E*
Conclusión breve confirmando que el comportamiento no cambió:
  En conclusión, al comparar los dos main (el obtenido desde JD-GUI y el de Eclipse) se puede ver que, aunque cambian los nombres de clases, métodos y variables por la ofuscación, la lógica y el flujo del programa siguen siendo exactamente los mismos. Ambos realizan las mismas operaciones, llaman a los mismos métodos en el mismo orden y producen los mismos resultados. Esto confirma que la ofuscación no modificó el comportamiento del programa, únicamente afectó la legibilidad del código.




