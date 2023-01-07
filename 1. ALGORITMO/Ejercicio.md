### REALIZA UN ALGORITMO SOBRE ALGUNA ACTIVIDAD EN TU VIDA COTIDIANA.

    TU RESPUETA AQUI



### DESARROLLA UN ALGORITMO QUE CALCULE LA EDAD DE UNA PERSONA CON BASE A LA OBTENCION DE SU FECHA DE NACIMIENTO.

    TU RESPUESTA AQUI
    Algoritmo Define_edad

	definir año_actual,mes_actual,dia_actual,año_nac,mes_nac,dia_nac,edad Como Entero;
	
	
	Escribir "Indique su año de nacimiento (a 4 dígitos): ";
	Leer año_nac;
	Escribir  "Indique su mes de nacimiento ( a 2 dígitos) : " ;
	Leer  mes_nac;
	Escribir "Indique su día de nacimiento (a 2 dígitos): ";
	Leer dia_nac;
	
	
	Escribir "Introduzca el año actual (a 4 dígitos)";
	Leer año_actual;
	Escribir "Introduzca el mes actual (a 2 dígitos)";
	Leer mes_actual;
	Escribir "Introduzca el dia actual (a 2 dígitos)";
	Leer dia_actual;
	
	Si mes_nac >= mes_actual Entonces
		edad<-(año_actual - año_nac) -1;
	SiNo
		Si mes_nac  < mes_actual Entonces
			edad<-(año_actual - año_nac) +1;	
		FinSi
		
	Si dia_nac >= dia_actual Entonces
		edad<-(año_actual - año_nac) -1 ;
	SiNo
		Si dia_nac  < dia_actual Entonces
			edad<-(año_actual - año_nac) + 1;	
		FinSi
		
	
	FinSi	
	
	FinSi	
	Escribir "su edad es:  ",edad, "años";
	
FinAlgoritmo




###  Realice un algoritmo que resuelva la siguiente situación: un producto tenía un precio inicial que debe solicitarse y ahora tiene un nuevo valor, mayor, que también deberá pedirse, determine el porcentaje de incremento del producto. 

    TU RESPUESTA AQUI
