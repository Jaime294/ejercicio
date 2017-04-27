Segunda parte: Ejercicio práctico (Solución)

Organización de ficheros: En la entrega del aplicativo alojado en un repositorio se encuentran tres archivos únicamente, no se encuentran dentro de la organización jerárquica que debe llevar un proyecto.


Comentarios: La intención principal de los comentarios de implementación y javadocs es ubicar a quien lea el código y responda a preguntas como quien, cuando y como hizo una solución, la documentación especificada por los archivos en el repositorio cuentan con una documentación pobre que no especifica debidamente la solución.


Visibilidad de atributos de instancias de clases: Las clases generadas no cuentan con funciones get ni set.


Referencias a miembros de una clase: Los constructores son debidamente instanciados y utilizados como se evidencia ya que, en LCDTester.java se instancia a ImpresorLCD.java.

Modificaciones en el código

•	Importar librería Javax.swing para visualizar los cuadros de dialogo

•	La clase LCDTester.Java, no está haciendo uso de la librería Javax.swing. Se puede prescindir de esta.

•	En la clase LCDTester.Java, las llaves de la declaración try/catch estaban mal colocados. La escritura correcta de dicha declaración es:
try {
    sentencias;
} catch (ClaseException e) {
    sentencias;
}


•	En la clase ImpresorLCD.java, los métodos adicionarLinea(), adicionarSegmento(), adicionarDigito(), imprimirNumero() y procesar() se cambiaron a public.

•	La línea 54 de la clase LCDTester.Java, se ha fragmentado en dos líneas que muestran una declaración y una asignación respectivamente; esto con el fin de una mejor legibilidad. Quedando de la siguiente forma:
ImpresorLCD impresorLCD;
impresorLCD = new ImpresorLCD();

Conclusiones
En general el código generado es legible y entendible para un usuario con gran conocimientos de codificación, pero la poca documentación del mismo, la falta de referencia y comentarios a las variables, dificultan en gran medida el entendimiento del mismo, como solución se propone documentar debidamente el código, hacer una inserción de métodos get y set de ser necesarios, organizar los ficheros en el orden establecido por el estándar esto con el fin de hacer un código limpio y entendible.
