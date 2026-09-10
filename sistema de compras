#include <stdio.h>
#include <string.h>
int main(){
    
    char item[50] = "";
    float preço = 0.0f;
    int quantidade = 0;
    char moeda[4] = "R$";
    float total = 0.0f;
    
    printf("qual item vc gostaria de comprar?: ");
    fgets(item, sizeof(item), stdin);
    item[strlen(item) - 1] = '\0';
    
    printf("qual é o valor do item?: ");
    scanf("%f", &preço);
    
    printf("quantos vc irá comprar?: ");
    scanf("%d", &quantidade);
    
    total = preço * quantidade;
    
    printf("\nvoce comprou %d %s(s)\n", quantidade, item);
    printf("o valor de sua compra foi: %s%.2f", moeda, total);
   
    
    return 0;
}
