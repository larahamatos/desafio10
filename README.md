# desafio10

# questao1
```java
        int[] a = {7, 9, 10, 14, 23, 23, 1, 15, 16, 2};
        int[] b = {1, 2, 3, 4, 5, 6, 7, 8, 9, 10};
        int[] c = new int[10];
        for (int i = 0; i < a.length; i++) {
            c[i] = a[i] + b[i];
            System.out.println(a[i] + " + " + b[i] + " = " + c[i]);
```
# questao2
```java
        int[] a = {7, 9, 10, 14, 23, 23, 1, 15, 16, 2};
        int[] b = {1, 2, 3, 4, 5, 6, 7, 8, 9, 10};
        int[] c = new int[10];
        for (int i = 0; i < a.length; i++) {
            c[i] = a[i] - b[i];
            System.out.println(a[i] + " - " + b[i] + " = " + c[i]);
```
# questao3 
```java
        int[] elementos = new int[10];
        Scanner ler = new Scanner(System.in);
        int maximo = elementos[0];
        int minimo = elementos[0];

        for (int x = 0; x < elementos.length; x++) {
            System.out.println("Digite um número: ");
            elementos[x] = ler.nextInt();

            if (elementos[x] > maximo) {
                maximo = elementos[x];
            } else if (elementos[x] < minimo) {
                minimo = elementos[x];
            }
        }
        System.out.println("\nMaior valor:" + maximo);
        System.out.println("Menor valor:" + minimo);
```
# questao4
```java
        Scanner ler = new Scanner(System.in);
        int[] vetor = new int[10];

        for (int x = 0; x < vetor.length; x++) {
            System.out.println("Digite um número: ");
            vetor[x] = ler.nextInt();

        }
        System.out.println("\nNúmeros PARES");
        for (int x = 0; x < vetor.length; x++) {

            if (vetor[x] % 2 == 0) {

                System.out.println("vetor[" + x + "]=" + vetor[x]);
