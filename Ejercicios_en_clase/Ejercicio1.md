Ejercicio que calcula el tiempo que tardaríamos en leer  los nombres de un determinado número de la poblacion
# algoritmo
# Diagrama de flujo

![image](https://user-images.githubusercontent.com/119735729/208263968-368cef06-130e-4f3f-8b52-bd84ede324b0.png)
# pseudocódigo
Algoritmo Tiempo_leer_nombres
	poblacion=0;
	tiempo_a_leer=2;
	segs=0;
	minutos=0;
	horas=0;
	dias=0;
	años=0;
	meses=0;
	
	Escribir "Ingresa el número de la población que quieres evaluar";
	Leer poblacion;
	
	segs = poblacion * tiempo_a_leer;
	minutos = segs/60;
	horas = minutos/60;
	dias = horas/24;
	años = dias/365;
	
	Escribir "segundos: " ,segs,"minutos: ",minutos, "horas: " ,horas, "dias: " ,dias, "años: " ,años, "meses: " , meses;
	
FinAlgoritmo
