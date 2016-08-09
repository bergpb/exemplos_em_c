#include <stdio.h>
#include <math.h>
#include <locale.h>
 
int main(void) {
	
	setlocale(LC_ALL,"");
	
	int num = 12345;
	int novonum=0;
 
	int i = 0;
	int contagem = 0;
	int temp = 0;
	
	/*printf("Digite sua conta: ");
	scanf("%i", &num);*/
 
	temp = num;
		
 
	while (temp>0) { //este while faz a contagem de algarismos baseado no valor digitado.
 
		temp = temp/10;
		printf("Temp igual a %d \n", temp);
		contagem++;
 
	}
 
	printf("Quantidade de algarismos igual a: %i \n\n", contagem);
 
	while(num > 0){ //este while realiza a separação e organização dos algarimos.
 
		i = num % 10;
		num = num / 10;
		
		printf("Num igual a %d \n", num);

		novonum = novonum + i*pow (10, contagem - 1);
		contagem--;
		
		printf("novonum igual a %d \n\n", novonum);
 
	}
 
	printf("Números inversamente organizados: %i", novonum);
	

	return 0;
	
}
