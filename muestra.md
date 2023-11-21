# Muestras

## Proyectos de Github

[![Muestra de Trabajo](github.png)](https://github.com/fernandezsuarezluis)

## Muestra de Trabajo

### Java
   ```java
   class areacuadrado{

	public static void main(String[] args){

		int lado=4;

		int area=lado*lado;

		System.out.println("area:" +area);
	}

}
```
### Kotlin
```kotlin
fun main() {
    val dni = readln()

    if (dni.length != 8) {
        println("DNI no válido")
    } else {
        val dniNumero = dni.substring(0, 8).toIntOrNull()
        val divisor = 23

        if (dniNumero != null) {
            val numeroletra = dniNumero % divisor
            when (numeroletra) {
                0 -> println("T")
                1 -> println("R")
                2 -> println("W")
                3 -> println("A")
                4 -> println("G")
                5 -> println("M")
                6 -> println("Y")
                7 -> println("F")
                8 -> println("P")
                9 -> println("D")
                10 -> println("X")
                11 -> println("B")
                12 -> println("N")
                13 -> println("J")
                14 -> println("Z")
                15 -> println("S")
                16 -> println("Q")
                17 -> println("V")
                18 -> println("H")
                19 -> println("L")
                20 -> println("C")
                21 -> println("K")
                22 -> println("E")
            }
        } else {
            println("DNI no válido")
        }
    }
}
```
