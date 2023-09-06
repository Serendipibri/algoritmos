Algoritmo volumen_y_area_cilindro_enPSeInt
	Escribir "ingresar el radio de la base del cilindro en cm" 
	leer r
	
	Escribir "ingresar la altura del cilindro en cm" 
	leer h
	
	//la formula del volumen del cilindro es Pi por area por altura, el area es radio al cuadrado(tenemos r=4 y h=8)
	
	//calcular el area de la base del cilindro (el circulo o radio al cuadrado)
	area_base=3.1416*r^2
	
	//la altura es 8
	altura=h
	
	//calcular el volumen
	volumen=area_base*h
	
	//calcular el area total se requiere el area lateral
	area_lado=2*3.1416*r*h
	
	//calcular el area total se suma area_total mas area_lado
	
	area_total= 2*area_base+area_lado
	
	Escribir "lel volumen es", volumen 
	Escribir "el area total es:", area_total
	
FinAlgoritmo
