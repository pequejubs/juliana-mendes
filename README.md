#include <stdio.h>
int main() {
	int n1;
	scanf("%d",&n1);
	if(n1 > 0) {
		printf("valor positivo");	
	}
	return 0;
}
#include <stdio.h>
int main() {
	int N;
	printf("Digite um valor para N\n");
	scanf("%d",&N);
	while(N != 5) {
		printf("Digite um novo valor para N\n");
		scanf("%d",&N);
	}
	printf("Finalmente foi digitado 5\n");
	return 0;	
}
