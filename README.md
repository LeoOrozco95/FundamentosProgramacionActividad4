# FundamentosProgramacionActividad4
Repositorio de ejercicios de estructura de control con javaScript

Ejercicio 1 
while (true) { // Use an infinite loop, breaking when a negative number is entered
            System.out.print("Introduzca número: ");
            // Check if the next input is an integer to avoid errors
            if (teclado.hasNextInt()) {
                num = teclado.nextInt();

                // Check if the number is negative to exit the loop
                if (num < 0) {
                    System.out.println("Número negativo introducido. Saliendo del programa.");
                    break; // Exit the while loop
                }

                cuadrado = num * num;
                System.out.println(num + "^2 es igual a " + cuadrado);

            } else {
                System.out.println("Entrada no válida. Por favor, introduzca un número entero.");
                teclado.next(); // Consume the invalid input to prevent an infinite loop
            }
        }

        System.out.print("Fin ...");
        teclado.close(); // Close the scanner
Ejercicio 2

Ejercicio 3

Ejercicio 4 

Ejercicio 5

Ejercicio 6

Ejercicio 7

Ejercicio 8

