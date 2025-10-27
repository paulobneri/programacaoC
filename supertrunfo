#include <stdio.h>

int main(){

    char estado1[2], estado2[2], codigo1[4], codigo2[4], cidade1[50], cidade2[50];
    int populacao1, populacao2;
    float area1, area2, pib1, pib2;
    int turistico1, turistico2;
    float densidade1, densidade2;
    float pibpc1, pibpc2;
    float superpoder1, superpoder2;

    //entrada de dados
    printf("Digite a letra correspondente ao estado da Carta 1: ");
    scanf("%s", &estado1);

    printf("Digite o codigo da Carta 1: ");
    scanf("%s", &codigo1);

    printf("Digite o nome da cidade da Carta 1: ");
    scanf(" %s", &cidade1);

    printf("Digite o número de habitantes da cidade da Carta 1: ");
    scanf(" %d", &populacao1);

    printf("Digite a area em km² da cidade da Carta 1: ");
    scanf("%f", &area1);

    printf("Digite o Produto Interno Bruto (PIB) da cidade da Carta 1: ");
    scanf("%f", &pib1);

    printf("Digite o numero de pontos turisticos da cidade da Carta 1: ");
    scanf(" %d", &turistico1);

    printf("\nDigite a letra correspondente ao estado da Carta 2: ");
    scanf("%s", &estado2);

    printf("Digite o codigo da Carta 2: ");
    scanf("%s", &codigo2);

    printf("Digite o nome da cidade da Carta 2: ");
    scanf(" %s", &cidade2);

    printf("Digite o número de habitantes da cidade da Carta 2: ");
    scanf(" %d", &populacao2);

    printf("Digite a area em km² da cidade da Carta 2: ");
    scanf("%f", &area2);

    printf("Digite o Produto Interno Bruto (PIB) da cidade da Carta 2: ");
    scanf("%f", &pib2);

    printf("Digite o numero de pontos turisticos da cidade da Carta 2: ");
    scanf(" %d", &turistico2);

    //calculos
    densidade1 = populacao1 / area1; 
    densidade2 = populacao2 / area2;
    
    pibpc1 = pib1 / populacao1;
    pibpc2 = pib2 / populacao2;

    superpoder1 = populacao1 + area1 + pib1 + turistico1 + pibpc1 + (1/densidade1);
    superpoder2 = populacao2 + area2 + pib2 + turistico2 + pibpc2 + (1/densidade2);
    

    //exposição de dados de cada carta
    printf("\n\nCARTA 1");
    printf("\nEstado: %s", estado1);
    printf("\nCódigo da carta: %s", codigo1);
    printf("\nCidade: %s", cidade1);
    printf("\nPopulação: %d", populacao1);
    printf("\nArea: %f km²", area1);
    printf("\nPIB: R$ %.2f", pib1);
    printf("\nPontos turisticos: %d", turistico1);
    printf("\nDensidade populacional: %f", densidade1);
    printf("\nPIB per capta: %f", pibpc1);
    printf("\nSuper Poder: %.2f", superpoder1);

    printf("\n\nCARTA 2");
    printf("\nEstado: %s", estado2);
    printf("\nCódigo da carta: %s", codigo2);
    printf("\nCidade: %s", cidade2);
    printf("\nPopulação: %d", populacao2);
    printf("\nArea: %f km²", area2);
    printf("\nPIB: R$ %.2f", pib2);
    printf("\nPontos turisticos: %d", turistico2);
    printf("\nDensidade populacional: %f", densidade2);
    printf("\nPIB per capta: %f", pibpc2);
    printf("\nSuper Poder: %.2f", superpoder2);

    //sequência de estruturas de decisões para avaliar cada item qual foi a carta vencedora
    
    printf("\n\n\nA SEGUIR TEREMOS A INDICAÇÃO DO ITEM ANALISADO E A INDICAÇÃO DA CARTA VENCEDORA:");
    
    if(populacao1>populacao2)
        printf("\n\nPOPULAÇÃO: Carta 1 (%s) venceu!", cidade1);

        else    
            printf("\n\nPOPULAÇÃO: Carta 2 (%s) venceu!", cidade2);

    if(area1>area2)
        printf("\nÁREA: Carta 1 (%s) venceu!", cidade1);

        else    
            printf("\nÁREA: Carta 2 (%s) venceu!", cidade2);

    if(pib1>pib2)
        printf("\nPIB: Carta 1 (%s) venceu!", cidade1);

        else    
            printf("\nPIB: Carta 2 (%s) venceu!", cidade2);

    if(turistico1>turistico2)
        printf("\nPontos Turísticos: Carta 1 (%s) venceu!", cidade1);

        else    
            printf("\nÁREA: Carta 2 (%s) venceu!", cidade2);

    //na condição seguinte, ao contrário de todas as outras, quem vence é o valor menor.
    if(densidade1>densidade2)
        printf("\nDensidade Populacional: Carta 2 (%s) venceu!", cidade2);

        else    
            printf("\nDensidade Populacional: Carta 1 (%s) venceu!", cidade1);

    if(pibpc1>pibpc2)
        printf("\nPIB per capta: Carta 1 (%s) venceu!", cidade1);

        else    
            printf("\nPIB per capta: Carta 2 (%s) venceu!", cidade2);

    if(superpoder1>superpoder2)
            printf("\nSuper Poder: Carta 1 (%s) venceu!", cidade1);

        else    
            printf("\nSuper Poder: Carta 2 (%s) venceu!", cidade2);

            
}
