/*
 * Click nbfs://nbhost/SystemFileSystem/Templates/Licenses/license-default.txt to change this license
 * Click nbfs://nbhost/SystemFileSystem/Templates/Classes/Main.java to edit this template
 */
package tp1.java.licence;

/**
 *
 * @author hp
 */
import java.util.Scanner;
public class TP1JAVALicence {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        // TODO code application logic here
        Scanner scanner = new Scanner(System.in);
        /** Exercice 1
         * System.out.print("Entrez un entier : ");
        int n = scanner.nextInt();
        if (n > 0) {
            System.out.print("Le nombre " + n + " est positif");
        }else if (n < 0){
            System.out.print("Le nombre " + n + " est negatif");
        }else
            System.out.print("Le nombre " + n + " est null");
        */
        /** Exercice 2
         * System.out.print("Veuillez saisir premiere nombre : ");
        int n1 = scanner.nextInt();
        System.out.print("Veuillez saisir deuxieme nombre : ");
        int n2 = scanner.nextInt();
        System.out.print("Veuillez saisir troisiemee nombre : ");
        int n3 = scanner.nextInt();
        int max;
        if (n1>n2 & n1>n3){
            max = n1;
            System.out.print("La valeur maximale premiere nombre : " +max);
        }else if (n2>n1 & n2>n3){
            max = n2;
            System.out.print("La valeur maximale est deuxieme nombre : " +max);
        }else if(n3>n1 & n3>n2){
            max=n3;
            System.out.print("La valeur maximale est troisiemee nombre : " +max);
        }
        */
        // Exercice 3
        /**
        System.out.print("Veuillez saisir le nombre : ");
        int mult = scanner.nextInt();

        int multiplication;

        for (int i = 0; i <= 10; i++) {
            multiplication = i * mult;
            System.out.println(i + " * " + mult + " = " + multiplication);
        }
        */
        /**
        int[] entiers = new int[10];

        System.out.println("Veuillez saisir 10 entiers :");

        int i = 0;
        while (i < 10) {
            entiers[i] = scanner.nextInt();
            i++;
        }

        System.out.print("Veuillez saisir N : ");
        int N = scanner.nextInt();

        int somme = 0;
        i = 0;

        while (i < N) {
            somme += entiers[i];
            i++;
        }

        System.out.println("La somme des " + N + " premiers entiers est : " + somme);
        */
        // Partie 2 Tableau
        /** Exercice 5
        System.out.println("Veuillez saisir n :");
        int n = scanner.nextInt();
        int[] entiers = new int[n];

        System.out.println("Veuillez saisir 10 entiers :");

        int i = 0;
        while (i < n) {
            entiers[i] = scanner.nextInt();
            i++;
        }
        System.out.println("La taille du tableau est : " + entiers.length);
        */
        //Exercice 6: 
        /* int[] entiers = new int[10];

        System.out.println("Veuillez saisir 10 entiers :");

        int i = 0;
        while (i < 10) {
            entiers[i] = scanner.nextInt();
            i++;
        }
        System.out.println("Quel est le nombre demander a recherche :");
        int d = scanner.nextInt();
        boolean trouve = false;
        for (int j = 0; j < 10; j++) {
            if (d == entiers[j]) {
                System.out.println("La position de votre nombre est :" + j);
                trouve = true;
                break;
            }
        }

        if (!trouve) {
            System.out.println("Le nombre demander a recherche introuvable");
        }
     */
    //Exercice 7
    /*System.out.println("Veuillez Saisir le Nombre N d'entier");
    int N = scanner.nextInt();
    int i=0;
    int[] entiers = new int[N]; 
    while(i <N){
        System.out.println("Saisir les nombres");
        entiers[i] = scanner.nextInt();
        i++;
    }
    int max = entiers[0];
    for(i=0;i<N;i++){
        if (max < entiers[i]){
        max = entiers[i] ;
        }
    }
    System.out.println("Le maximum est : " + max);*/
    // Partie 3 Matriice
    // Exercice 8
    /* int[][] mat =new int[3][3];
    for (int i = 0; i < 3; i++) {
    for (int j = 0; j < 3; j++) {
        System.out.print("Entrer l'element [" + i + "][" + j + "] : ");
        mat[i][j] = scanner.nextInt();
    }
    System.out.println("La matrice est :");

    for (int ii = 0; ii < 3; ii++) {
        for (int jj = 0; jj < 3; jj++) {
            System.out.print(mat[ii][jj] + " ");
        }
        System.out.println();
    }
    }*/
    //Exerciec 9
    /*int[][] mat =new int[3][3];
    int somme = 0;
    for (int i = 0; i < 3; i++) {
    for (int j = 0; j < 3; j++) {
        System.out.print("Entrer l'element [" + i + "][" + j + "] : ");
        mat[i][j] = scanner.nextInt();
    }
}

    for (int i = 0; i < 3; i++) {
        for (int j = 0; j < 3; j++) {
            somme += mat[i][j];
        }
    }
    System.out.println("La somme des elements = " + somme);*/
    //Exercice 10
    /*int[][] mat = new int[3][3];
    int[][] transpose = new int[3][3];
    int somme = 0;
    for (int i = 0; i < 3; i++) {
        for (int j = 0; j < 3; j++) {
            System.out.print("Entrer [" + i + "][" + j + "] : ");
            mat[i][j] = scanner.nextInt();
        }
    }

    for (int i = 0; i < 3; i++) {
        for (int j = 0; j < 3; j++) {
            transpose[j][i] = mat[i][j];
        }
    }

    // mat origine
    System.out.println("Matrice originale :");
    for (int i = 0; i < 3; i++) {
        for (int j = 0; j < 3; j++) {
            System.out.print(mat[i][j] + " ");
        }
        System.out.println();
    }

    // mat trans
    System.out.println("Transposee :");
    for (int i = 0; i < 3; i++) {
        for (int j = 0; j < 3; j++) {
            System.out.print(transpose[i][j] + " ");
        }
        System.out.println();
    }
    for (int i = 0; i < 3; i++) {
        for (int j = 0; j < 3; j++) {
            somme += transpose[i][j];
        }
    }
    System.out.println("La somme des elements = " + somme);*/
    //Part 4
    //Exercice 11
    /*System.out.println("Veuillez saisir votre chaine : ");
    String s = scanner.nextLine();
    System.out.println("La longueure est : " +s.length());
    //Exercice 12

    // Compter voyelles
    int nbVoyelles = 0;

    for (int i = 0; i < s.length(); i++) {
    char c = s.charAt(i);

    if (c == 'a' || c == 'e' || c == 'i' || c == 'o' || c == 'u' ||
        c == 'A' || c == 'E' || c == 'I' || c == 'O' || c == 'U') {
        nbVoyelles++;
        }
    }

    System.out.println("Nombre de voyelles = " + nbVoyelles);*/
    // exercice 13
    /*System.out.println("Veuillez saisir votre chaine : ");
    String s = scanner.nextLine();
    String inverse = "";

    for (int i = s.length() - 1; i >= 0; i--) {
        inverse += s.charAt(i);
    }

    System.out.println("Chaine inverszz : " + inverse);*/
    // 14
    System.out.println("Veuillez saisir votre chaine : ");
    String s = scanner.nextLine();
    String inverse = "";
    for (int i = s.length() - 1; i >= 0; i--) {
            inverse += s.charAt(i);
        }

        if (s.equalsIgnoreCase(inverse)) {
            System.out.println("C'est un palindrome");
        } else {
            System.out.println("Ce n'est pas un palindrome");
        }
    }
    }
   

    
    

