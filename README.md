Algoritmo escribe_holamundo
	escribir "hola mundo!"
	
FinAlgoritmo


Algoritmo f_celsius
	Escribir "ingrese el valor en farenheits que desea transformar"
	leer a
	f<-(a-32)*(5/9)
	escribir "la medida en celsius es: " f
	
FinAlgoritmo

Algoritmo hipotenusa
definir a, b, suma, res Como Real
	escribir "ingrese la medida de uno de los catetos"
	leer a
	escribir "ingrese la medida del otro cateto"
	leer b
	suma<-(a*a)+(b*b)
	res<-raiz(suma)
	escribir "la hipotenusa del triangulo es " res
	
FinAlgoritmo
