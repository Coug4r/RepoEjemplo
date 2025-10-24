# Aprendiendo Marckdown
Mis primeros *pasos* en **Marckdown**, que es un ___formato___ de marcado de ***archivos de texto.***

A continuación una __lista__:
* item 1
* item 2
    * item 2.1
    * item 2.2
* item 3

A continuación una __tabla__:

| _Código_ | _NOmbre_ | _Precio_ |
|   :-:    |   -    |   -:    |
|   1    |  tv    |  553.99|
|   2    |Computador|1687.23|
|   3    | Celular|  791.51 |

A continuacion un _enlace o link_:
[Pagina de Google](https://www.google.com/).

![Logo de Python](https://cdn-icons-png.flaticon.com/256/5968/5968286.png)

A continuacion el codigo de un programa:

    import java.util.Scanner;
    public class Saludo2 {
        public static void main(String[] args) {
            Scanner sc = new Scanner(System.in);
            String nombre;
            System.out.println("Dime tu nombre: ");
            nombre = sc.nextLine();
            System.out.print("Hola "+ nombre);
            System.out.println(", encantado de conocerte!");
        }
    }