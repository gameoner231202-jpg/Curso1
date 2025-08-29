![Diagrama de condicionales](https://msc-itorizaba.mx/wp-content/uploads/2019/09/logomsc.png)

# 🦉 Tema 1: Suma de Dos Números en Java

---

## 🧠 Objetivo

Aprender a usar `Scanner` en Java para ingresar datos desde el teclado y realizar operaciones aritméticas básicas.

---

## 📄 Instrucciones

1. Abre el archivo `Suma.java` o `Main.java` (según cómo esté nombrado).
2. Lee el código que ya está escrito.
3. Ejecuta el programa en Replit.
4. Ingresa distintos números cuando el programa lo solicite.
5. Completa la **tarea al final** de este documento.

> 💡 **Nota:** Si no tienes una cuenta en Replit, puedes crearla gratuitamente en 👉 [https://replit.com](https://replit.com)

---

## 👨‍💻 Código actual

```java
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.print("Ingresa el primer número: ");
        int numero1 = scanner.nextInt();

        System.out.print("Ingresa el segundo número: ");
        int numero2 = scanner.nextInt();

        int suma = numero1 + numero2;

        System.out.println("La suma es: " + suma);

        scanner.close();
    }
}

