# C-digos-lenguaje-c
Códigos realizados durante el segundo semestre de mecatrónica por el alumno jimenez tadeo Ruben Alejandro
#include <stdio.h>
#include <stdlib.h>

int main () {
     double aja = 2;
     double beta = 3;
     double casa = 5;
     
    printf("%f", aja*beta*casa);
    
    printf ("\n");
    
    return 0;
}

#include <stdio.h>
#include <stdlib.h>

int main () {
     double aja = 5;
     double beta = 2;
     
     
    printf("%f", aja/beta);
    
    printf ("\n");
    
    return 0;
}

#include <stdio.h>
#include <stdlib.h>

int main () {
     double r = 5;
     double π = 3.1416;
     double ² = 5;
     
     
    printf("%f", π*r*²);
    
    printf ("\n");
    
    return 0;
}

#include <stdio.h>
#include <stdlib.h>

int main () {
      int c =5;
      
     printf ("c : %d\n" , c);
     printf ("c++ : %d\n" , c++);
    printf ("c : %d\n" , c);
    
    int d = 10;
   printf ("d : %d\n" , d);
   printf ("d : %d\n" , --d);
   printf ("d : %d\n" , d);
   
    return 0;
}

#include <stdio.h>
#include <stdlib.h>

int main () {
      int x = 5;
      int y = 10;
      int z = ++x * y--;
      
      printf ("x : %d\n", x);
      printf ("y : %d\n", y);
      printf ("z : %d\n", z);
      
    return 0;
}

#include <stdio.h>
#include <stdlib.h>

int main () {
      int p = 5;
      int q = 1;
      int r = 2;
      int w = 3;
      int x = 9;
      int y = 6;
      int z;
      z= p * r %
      printf ("z : %d\n", z);
      
    return 0;
}

#include <stdio.h>
#include <stdlib.h>

int main () {
      printf ("1 + 2 * 3 : %d\n", 1+2*3);
      printf ("(1 + 2) * 3 : %d\n", (1+2)*3);
      printf ("1 + (2 * 3) : %d\n", 1+(2*3));
      
    return 0;
}//fin main 

#include <stdio.h>

int main() {
    // Declarar variables de tipo float para mayor precisión
    float resultado;

    // Calcular la expresión
    resultado = (1.0 / 3) + (3.0 / 5) + (1.0 / 30) / (23.0 / 30);

    // Imprimir el resultado con cuatro decimales
    printf("El resultado es: %.4f\n", resultado);

    return 0;
}

#include <stdio.h>
#include <stdlib.h>
int main() {
    double resultado;
    
    double d = 2.0 - (1.0 / 4.0);
    double c = 2.0 / d;
    double b= 1.0 + c;
    double a = 2.0 / b;
    resultado = 5.0 + a;
    printf("%.10f\n", resultado);
    
    return 0;
}

#include <stdio.h>

int main (){ 

printf (" ****Y*******\n");

printf("true && true: %d\n", (1 && 1));

printf ("true && false: %d\n", (1 && 0));

printf ("false && true: %d\n", (0 && 1));

printf ("false && false: %d\n", (0 && 0));
 
 printf (" ****** OR ******\n");

printf (" true || true : %d\n", (1 || 1));

printf (" true || false : %d\n", (1 || 0));

printf (" false || true : %d\n", (0 || 1));

printf (" false || false : %d\n", (0 || 0));

printf (" ****** XOR ******\n");

printf (" true ^ true : %d\n", (1 ^ 1) );

printf (" true ^ false : %d\n", (1 ^ 0) );

printf (" false ^ true : %d\n", (0 ^ 1) );

printf (" false ^ false : %d\n", (0 ^ 0) );

return 0;
}

#include <stdlib.h>

int main() { 
int P = 1; 
int R = 1; 
int Q = 0; 
int T = 0;

printf("P & R: %d\n", P &&R);
printf("Q || T: %d\n", Q || T);
printf("P & Q o R & T: %d\n", (P && Q) | (R && T));
printf("P | Q || R || T: %d\n", P ^ Q ^ R ^ T);
printf("! Q & ! T: %d\n", (!Q && !T));
printf("!!! P: %d\n", !!!P);


return 0;

}

#include <stdlib.h>

int main() { 
printf("%d\n", 3>5);
printf("%d\n", 3<5);
printf("%d\n", 3==5);
printf("%d\n", 3!=5);

return 0;

}

#include <stdio.h>

int main() {
    int w = 9;
    int x = 3;
    int y = 7;
    int z = -2;

    printf("1) x < y AND w > z: %d\n", (x < y) && (w > z));
    printf("2) x >= w XOR z == y: %d\n", (x >= w) ^ (z == y));
    printf("3) y <= x OR x == w: %d\n", (y <= x) || (x == w));
    printf("4) w == 9 OR w *= 3: %d\n", (w == 9) || (w *= 3));  
    printf("5) y > z AND z < x: %d\n", (y > z) && (z < x));
    printf("6) NOT w != 9: %d\n", !(w != 9));

    return 0;
}

#include <stdio.h>

int main () {

int numero =34;

if (numero %2 == 0) {

printf("El numero es par\n");

}

printf ("Fin del programa\n");

return 0;

} 


#include <stdio.h>

int main () {

int numero =35;

if (numero %2 == 0) {

printf("El numero es par\n");

}

printf ("Fin del programa\n");

return 0;

} 


#include <stdio.h>

int main () {
int numero =99;
if (numero < 100) {

   printf("El número es menor que 100 ");
   if (numero > 50)
   printf(" y mayor que 50 \n");
}

printf ("Fin del programa\n");

return 0;
}


#include <stdio.h>

int main (){
int anio;
int sala;
int por;
puts ("Ingresa tu antiguedad");
scanf("%d", &anio);
if (anio >= 5) {
puts("ingresa tu salario");
scanf("%d", &sala);
if((sala*100)/10>100);{
printf("Felicidades tu crédito aprobado");
}
}
return 0;
}

#include <stdio.h>
int main () {
int numero = 80;
if (numero < 50)
printf(" El número es menor que 50 ");
printf(" El número es mayor que 50");
printf (" Fin del programa\n");
return 0;
}


#include <stdio.h>
int main () {

int descuento= 10;
int descuentoCliente = 20;
int cliente = 0;
int z=0;

z = (cliente)? descuentoCliente: descuento;

printf ("El descuento es de %d \% \n", z);

printf ("Fin del programa\n");

return 0;
}


#include <stdio.h>
int main () {

int contador = 3;

while (contador < 3 ){

printf ("Hola \n");

contador++;

}

printf ("Fin");

return 0;

}// Fin main.

#include <stdio.h>
int main () {

int numero = 1;

while (numero <= 1000 ){

printf ("%d,", numero);

numero++;

}


return 0;

}




