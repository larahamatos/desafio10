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
```
# questao5
```java
        Scanner ler = new Scanner(System.in);
        int[] vetor = new int[10];

        for (int x = 0; x < vetor.length; x++) {
            System.out.println("Digite um número: ");
            vetor[x] = ler.nextInt();

        }
        System.out.println("\nNúmeros ÍMPARES");
        for (int x = 0; x < vetor.length; x++) {

            if (vetor[x] % 2 != 0) {

                System.out.println("vetor[" + x + "]=" + vetor[x]);
```
# questao6
```java
        int[] vetor = new int[10];
        int i, soma, quant;
        double media;
        Scanner ler = new Scanner(System.in);

        soma = 0;
        quant = 0;

        System.out.println("Digite 10 números inteiros: ");
        for (i = 0; i < 10; i++) {
            vetor[i] = ler.nextInt();
        }

        for (i = 0; i < 10; i++) {
            if (i % 2 == 0) {
                soma += vetor[i];
                quant++;
            }
        }
        media = (double) soma / quant;
        System.out.println("Média dos valores nas posições pares: "+media);
```
# questao7
```java
        int [] vetores = new int[10];
        int x, contador;
        Scanner ler = new Scanner(System.in);
        contador = 0;

        System.out.println("Digite 10 números inteiros:");
        for (x = 0; x < 10; x++) {
            vetores [x] = ler.nextInt();
        }

        for (x = 0; x < 10; x++) {
            if (x % 2 == 0) {
                contador++;
            }
        }

        System.out.println("Quantidade de elementos em índices pares: "+contador);
```
# questao8
```java
int[] vetorOriginal = new int[30];
        int[] vetorModificado = new int[30];
        int x;
        Scanner ler = new Scanner(System.in);

        System.out.println("Digite 30 números inteiros (use 0 para representar nulo): ");
        for (x = 0; x < 30; x++) {
            vetorOriginal[x] = ler.nextInt();
        }

        for (x = 0; x < 30; x++) {
            if (vetorOriginal[x] == 0) {
                vetorModificado[x] = 10;
            } else {
                vetorModificado[x] = vetorOriginal[x];
            }
        }

        System.out.println("Vetor original: ");
        for (x = 0; x < 30; x++) {
            System.out.print(vetorOriginal[x] + " ");
        }

        System.out.println();
        System.out.println("Vetor modificado (com 0 substituído por 10):");
        for (x = 0; x < 30; x++) {
            System.out.print(vetorModificado[x] + " ");
```
# questao9
```java
        Scanner ler = new Scanner(System.in);
        int[] vetorA = new int[10];
        int[] vetorB = new int[10];
        int[] vetorResultado = new int[10];
        int x;
        
        System.out.println("Digite 10 números inteiros para o primeiro vetor: ");
        for (x = 0; x < 10; x++) {
            vetorA[x] = ler.nextInt();
        }

        System.out.println("Digite 10 números inteiros para o segundo vetor: ");
        for (x = 0; x < 10; x++) {
            vetorB[x] = ler.nextInt();
        }

        for (x = 0; x < 10; x++) {
            vetorResultado[x] = vetorA[x] * vetorB[x];
        }

        System.out.println("Vetor que gerou da multiplicação: ");
        for (x = 0; x < 10; x++) {
            System.out.print(vetorResultado[x] + " ");
```
# questao10
```java
        Scanner ler = new Scanner(System.in);
        int[] vetorA = new int[10];
        int[] vetorB = new int[10];
        int y, x;

        System.out.println("Digite 10 números inteiros para o vetor A: ");
        for (y = 0; y < 10; y++) {
            vetorA[y] = ler.nextInt();
        }
        x = 9;
        for (y = 0; y < 10; y++) {
            vetorB[y] = vetorA[x];
            x--;
        }
        System.out.print("Vetor B (ordem inversa do vetor A): ");
        for (y = 0; y < 10; y++) {
            System.out.print(vetorB[y] + " ");
```
