## EJERCICIO 1

¿Qué tipo de dato debe tener una variable para representar la calificación promedio de un
curso?

      TU RESPUESTA AQUI
      Dato tipo float, real

¿Qué tipo de dato debe tener una variable para representar el número de personas en un
hogar?

      TU RESPUESTA AQUI
      Dato tipo integer, entero

¿Qué tipo de dato debe tener una variable para contener el nombre de pila de una persona?

      TU RESPUESTA AQUI
      Dato tipo string, cadena

¿Qué tipo de dato debe tener una variable para registrar si está lloviendo o no?

      TU RESPUESTA AQUI
      Dato tipo boolean

¿Qué tipo de dato debe tener una variable para representar la cantidad de dinero que
tienes?

      TU RESPUESTA AQUI
      Dato tipo float, real
      
## EJERCICIO 2

Realiza un algoritmo que calcule el promedio de un alumno el cual tiene cuatro calificaciones, una por periodo, de cada materia.

      TU ALGORITMO AQUI
      
      Algoritmo Promedio
      Inicio
	Definir Nombre_Alumno, Materia como cadena;
	Definir Cal1, Cal2, Cal3, Cal4, Prom Como Real;
	
	Escribir "Ingrese su nombre";
	Leer Nombre_Alumno;
	Escribir "Indique la materia";
	Leer Materia;
	Escribir "Ingrese su primera calificación";
	Leer Cal1;
	Escribir "Ingrese su segunda calificación";
	Leer Cal2;
	Escribir "Ingrese su tercera calificación";
	Leer Cal3;
	Escribir "Ingrese su cuarta calificación";
	Leer Cal4;
	
	Prom=(Cal1+Cal2+Cal3+Cal4) / 4;
	
	Escribir "El Promedio final del Alumno: ", Nombre_Alumno, " en : ", Materia, " es de: ", Prom;
	
	
      FinAlgoritmo
      
      
## EJERCICIO 3

Realiza un algoritmo para un programa que solicite al usuario su nombre y le salude usando ese nombre

      TU ALGORITMO AQUI 
      
      Algoritmo Saludo
      Inicio
	Definir Nombre como cadena;
	
	Escribir "Ingrese su nombre";
	Leer Nombre;
	
	Escribir " Hola ", Nombre, " Gusto en saludarte. Deseo que tengas un excelente día";
	
      FinAlgoritmo

## EJERCICIO 3

Realiza un algoritmo para  un programa que solicite al usuario ingresar la cantidad de kilómetros recorridos por una motocicleta y la cantidad de litros de combustible que consumió durante ese recorrido. El consumo por kilómetro es de 20.8

      TU ALGORITMO AQUI  
      
      Algoritmo kilometraje
      Inicio
	Definir cant_km , consumo Como Real;
	combustible_x_km<-20.8;
	
	
	Escribir "Introduzca el kilometraje recorrido por su motocicleta"
	Leer cant_km;
	consumo<-cant_km*combustible_x_km;
	
	Escribir "El combustible consumido durante su recorrido es de : " , consumo, " litros ";
	
      FinAlgoritmo

      

Ahora llevalos a PSINT
