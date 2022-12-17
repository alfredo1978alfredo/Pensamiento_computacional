Ejericio que calcula el tiempo que tardariamos en leer los nombre de un determinado numero de poblacion.
# ALGORITMO 
![image](https://user-images.githubusercontent.com/119713481/208264015-2750b140-aba5-4745-aa0f-69c41e6ad28c.png)

# SEUDOCODIGO

    Algoritmo sin_titulo
	poblacion =0
	tiempo_a_leer=2
	seg=0
	minutos=0
	horas=0
	dias=0
	mes=0
	años=0
	
	Escribir "Ingresa el numero de poblacion que quieres evaluar"
	Leer poblacion	
	Escribir poblacion	
	
	seg = poblacion * tiempo_a_leer
	Imprimir seg
	
	minutos=seg/60
	Imprimir minutos
	
	horas=minutos/60
	Imprimir  horas
	
	dias=horas/24
	Imprimir dias
	
	años=dias/365
	Imprimir años
	
	meses=dias / 12
	Imprimir meses
	
	
	Escribir "Te tardarias: ", años , " años y ", meses , " en leer todos los nombres del planeta"
	
		
	
FinAlgoritmo
