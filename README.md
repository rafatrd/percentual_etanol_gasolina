# percentual_etanol_gasolina
# percentual etanol gasolina
#include <stdio.h>
#include <stdlib.h>

/* run this program using the console pauser or add your own getch, system("pause") or input loop */

int main(int argc, char *argv[]) {
	//porcentual etanol vs gasolina 
	
	float etanol, gasolina;
	
	printf("Qual o valor atual do etanol? ");
	scanf("%f", &etanol );
	
	printf("Quala o valor atual da gasolina? ");
	scanf("%f", &gasolina);
	
	//calculo do etanol e gasolina 
	printf("O percentual e: %f",(etanol/gasolina));
	
	
	
	
	
	return 0;
}