# utfpr-hello-world
Um simples repositório para testar o GitHub
# Engenharia de Software
#### Introdução a Engenharia de Software
1. Meu primeiro repositório no GitHub

A baixo um código e C, para calcular as raizes pela Fórmula de Bhaskara 



```C
	#include <stdio.h>
	#include <math.h>
	int main (){
		float a, b, c, delta, x1, x2;
		
		scanf("%f %f %f", &a, &b, &c);
		
		delta = (b*b) - 4 * a * c;
		x1 = (-b + sqrt(delta))/(2*a);
		x2 = (-b - sqrt(delta))/(2*a);
		
			if (delta<0 || a==0){
			printf("Impossivel calcular\n");	
		}
		else{
			if(delta != 0 || a>0){
			printf("R1 = %.5f\n", x1);
			printf("R2 = %.5f\n", x2);
		}
		}		
		return 0;
	}
```
