# Tarea_colaborativa_GarridoGarc-a_Alejandro
Funcion Saludar
	Escribir "Hola mundo";
FinFuncion 

Funcion res <-CalcularDoble(num)
	definir res como numerico;
	res<- num*2;
FinFuncion

Funcion Triplicar (num por referencia )
	num <-num*3;
FinFuncion 


Algoritmo Pruebafuncion
	definir x  como entero;
	escribir "llamada a la funcion Saludar ";
	Saludar();
	escribir "Ingrese un valor numerico para x:";
	leer x;
    escribir "llamada a la funcion CalcularDoble (pasaje por valor)";
    escribir "el doble de" ,x ,"es", CalcularDoble(x);
    escribir "el valor orginal de x es ", x ;
    Escribir " llamada a la funcion Triplicar (pasaje por referencia)";
	Triplicar(x);
	escribir " el nuevo valor de x es", x ;
FinAlgoritmo
