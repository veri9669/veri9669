### Hi there š

<!--
**veri9669/veri9669** is a āØ _special_ āØ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- š­ This is a C++ addition, subtraction, division and multiplication calculator program. ...
- š± Iām currently learning ...
- šÆ Iām looking to collaborate on ...
- š¤ Iām looking for help with ...
- š¬ Ask me about ...
- š« How to reach me: ...
- š Pronouns: ...
- ā” Fun fact: ...
-->
#include <stdio.h>
#include <stdlib.h>

int main(void){
float x=0,y=0,resultado=0;   
int op=0;  

do{

printf("\n\t1-SOMA\n\t2-SUBTRACAO\n\t3-MULTIPLICAO\n\t4-DIVISAO");
scanf("%i",&op);
printf("\nDigite o primeiro numero :");
scanf("%f",&x);
printf("\nDigite o segundo numero :");
scanf("%f",&y);
switch(op){
	case 1: 
	resultado = x + y;
	break;
	case 2:
	resultado = x - y;
	break;
	case 3:
	resultado = x*y;
	break;
	case 4: 
	resultado = x/y;
	break;
	default:
printf("\nDigite uma opcao valida");
break;

}
printf("\n\t O resultado e: %0.2f",resultado);
printf("\nDigite 1 para continuar :");
scanf("%i",&op);
 
}while(op==1,2,3,4);


}
