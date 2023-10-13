<p align="center">
    <img src="![Alt text](<foto de lomba.jpg>)" alt="Logo Java">
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

## 2. CALCULADORA DE NOTAS

este codigo es una calculadora de notas diseñada para calularel promedio de notas que usuario decida darle , codigo simple de la cantidad total de notas divida entre el numero de los datos ingresado para dar el promedio este codigo nos puede servir a a hora de sacar promedio de notas de una asignatura 


<!-- "

import javax.swing.JOptionPane;

public class CalculadoraNotas {
   public static void main(String[] args) {
       double cantidadNotas = Double.parseDouble(JOptionPane.showInputDialog("Ingrese el número de notas: "));
       double notas[] = new double[(int) cantidadNotas];

       for (int i = 0; i < cantidadNotas; i++) {
           notas[i] = Double.parseDouble(JOptionPane.showInputDialog("Ingrese la nota" + (i + 1) + ": "));
       }

       double notaMaxima = notas[0];
       double notaMinima = notas[0];
       double sumaNotas = 0;

       for (int i = 0; i < cantidadNotas; i++) {
           if (notas[i] > notaMaxima) {
               notaMaxima = notas[i];
           }
           if (notas[i] < notaMinima) {
               notaMinima = notas[i];
           }
           sumaNotas += notas[i];
       }

       double promedio = (double) sumaNotas / cantidadNotas;

       JOptionPane.showMessageDialog(null, "Nota Máxima: " + notaMaxima);
       JOptionPane.showMessageDialog(null, "Nota Mínima: " + notaMinima);
       JOptionPane.showMessageDialog(null, "Promedio de Notas: " + promedio);
   }
} -->

## 3. GESTOR DE NOTAS

este codigo esta diseñado para asginar una variables = (Notas) a las asignaturas prediseñadas por el codigo con esto podemos tener una persepcion de que es lo que significa usar las arrays en un codigo para poder asi identificar y poder usarlos a futuro

<!-- GESTOR DE NOTAS

import javax.swing.JOptionPane;

public class GestorDeAsignaturas {
    public static void main(String[] args) {
    	
        String[] asignaturas = {"APO", "CÁLCULO", "ÁLGEBRA", "CLOUD", "DELITOS"};
        double[] notas = new double[5]; 

        for (int i = 0; i < asignaturas.length; i++) {
            try {
                double nota = Double.parseDouble(JOptionPane.showInputDialog(null, "Ingrese la nota para " + asignaturas[i] + ": ", "Gestor De Asignaturas", JOptionPane.QUESTION_MESSAGE));
                notas[i] = nota;
            } catch (Exception e) {
                JOptionPane.showMessageDialog(null, "Por favor, ingrese una nota válida para " + asignaturas[i], "Error", JOptionPane.ERROR_MESSAGE);
                i--;
            }
        }

        String resultado = "Notas de asignaturas:\n";
        for (int i = 0; i < asignaturas.length; i++) {	
            resultado += asignaturas[i] + ": " + notas[i] + "\n";
        }

        JOptionPane.showMessageDialog(null, resultado, "Resultados", JOptionPane.QUESTION_MESSAGE);
    }
} -->
