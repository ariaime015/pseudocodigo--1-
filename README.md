# pseudocodigo--1-
Algoritmo tarea
	contador=0;
	alturaing=0; 
	alturaprom=0;
	alturasuma=0;
	contadorH=0;
	contadorM=0;
	promH=0;
	promM=0;
	alturaMayorM=0;
	alturaBajoH=0;
	Escribir "Bienvenido al senso" ; 
	Escribir "ingrese la altura,el sexo del individuo (mujer=1 , hombre=cualqueir otro valor) " ;
	Mientras (contador<=10)
		Leer  alturaing; 
		leer sexo;
		alturasuma = alturasuma+alturaing; 
		contador=contador+1;
		si sexo=1
			si alturaing>alturaMayorM
				alturaMayorM=alturaing;
			FinSi
			contadorM=contadorM+1;
			SiNo
				contadorH=contadorH+1;
				si alturaing<alturaBajoH
					alturaBajoH=alturaing;
				FinSi
		FinSi
	FinMientras
	promH=contadorH*10;
	promM=contadorM*10; 
	alturaprom=alturasuma/contador; 
	Escribir "El promedio de la suma es:", alturaprom;
	Escribir  "El promedio de hombres es:", promH;
	Escribir  "El promdeio de mujeres es:", promM;
	Escribir "La menor altura en hombre es:", alturaBajoH;
	Escribir "la mayor altura en mujer es:", alturaMayorM;
FinAlgoritmo
