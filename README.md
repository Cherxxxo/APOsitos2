<p align="center">
    <img src="https://seeklogo.com/images/J/java-logo-7833D1D21A-seeklogo.com.png" alt="Logo Java">
</p>

<p align="center">
    💻 
</p>

<p align="center">
    <img src="https://img.shields.io/badge/GitHub-%23121011.svg?style=for-the-badge&logo=github&logoColor=white">
</p>

# Trabajo de APOsitos 

Creado por cherxxxo_StainGun_andreflombana 

# Descripción de nuestro trabajo

el siguiente trabajo por parte del el usuarios dueños del repositorio dara a mostra ejercicios puestos a realizacion en la clase de segundo semestres "APOII" donde se podra evidencia cada uno de los ejercicios trabajados con su respectiva explicacion y codigo , para complenmentar el trabajo de cloud y poner a evidencia el uso y manejo de tanto GitHub.

## 1. CALCULADORA FACTORIAL

la calcudora factorial es un codigo ultilazo para tener una variable y que esta se multiplique por su antecesores hasta llegar a 1 un ejemplo claro seria el numero 4 que hara el siguiente recorrido "4=4*3*2*1" y mostrara en el panel el resutaldo

el codigo es el siguiente:

<!-- "

public class MenúConJOptionPane {

    public static void main(String[] args) {
        boolean quiereCalcularOtro = true;

        while (quiereCalcularOtro) {
            int numero = obtenerNumero();
            long factorial = calcularFactorial(numero);
            mostrarResultado(numero, factorial);

            String respuesta = JOptionPane.showInputDialog("¿Desea calcular otro factorial? (Sí/No)");
            if (!respuesta.equalsIgnoreCase("Sí")) {
                quiereCalcularOtro = false;
            }
        }
    }

    public static int obtenerNumero() {
        int numero = 0;
        boolean numeroValido = false;

        while (!numeroValido) {
            numero = Integer.parseInt(JOptionPane.showInputDialog("Ingrese un número entero positivo:"));
            if (numero > 0) {
                numeroValido = true;
            } else {
                JOptionPane.showMessageDialog(null, "Ingrese un número positivo.");
            }
        }

        return numero;
    }

    public static long calcularFactorial(int numero) {
        long factorial = 1;
        for (int i = 1; i <= numero; i++) {
            factorial *= i;
        }
        return factorial;
    }

    public static void mostrarResultado(int numero, long factorial) {
        JOptionPane.showMessageDialog(null, "El factorial de " + numero + " es " + factorial);
    }
}" -->

