# xadrez.c
Movimentação das peças de xadrez usando estruturas de repetição em C. 

```

#include <stdio.h>

int main() {
    // ----------- Movimento da Torre -----------
    // Usando estrutura FOR
    int i;
    int movimentoTorre = 5;
    printf("Movimento da Torre:\n");
    for (i = 1; i <= movimentoTorre; i++) {
        printf("Direita\n");
    }

   #include <stdio.h>

int main() {
    // ----------- Movimento da Torre -----------
    // Usando estrutura FOR
    int i;
    int movimentoTorre = 5;
    printf("Movimento da Torre:\n");
    for (i = 1; i <= movimentoTorre; i++) {
        printf("Direita\n");
    }

    // ----------- Movimento do Bispo -----------
    // Usando estrutura WHILE
    int j = 0;
    int movimentoBispo = 5;
    printf("\nMovimento do Bispo:\n");
    while (j < movimentoBispo) {
        printf("Cima Direita\n");
        j++;
    }

    // ----------- Movimento da Rainha -----------
    // Usando estrutura DO-WHILE
    int k = 0;
    int movimentoRainha = 8;
    printf("\nMovimento da Rainha:\n");
    do {
        printf("Esquerda\n");
        k++;
    } while (k < movimentoRainha);

    return 0;
}
 // ----------- Movimento do Bispo -----------
    // Usando estrutura WHILE
    int j = 0;
    int movimentoBispo = 5;
    printf("\nMovimento do Bispo:\n");
    while (j < movimentoBispo) {
        printf("Cima Direita\n");
        j++;
    }

    // ----------- Movimento da Rainha -----------
    // Usando estrutura DO-WHILE
    int k = 0;
    int movimentoRainha = 8;
    printf("\nMovimento da Rainha:\n");
    do {
        printf("Esquerda\n");
        k++;
    } while (k < movimentoRainha);

    return 0;
}
