# MayorMenor
código para imprimir 10 números solicitados y luego  ordenados de mayor a menor y de menor a mayor 
Texto <HTML></HTML>
Algoritmo minMaxSerieEnteros
	Definir serie Como Entero
	Definir maximo Como Entero
	Definir minimo Como Entero
	Definir totalElementos Como Entero
	Definir totalBucle Como Entero

	totalElementos <- 10
	totalBucle <- totalElementos-1

	Dimension numElementos[totalElementos]
	numElementos[1] <- 10
	numElementos[2] <- 5
	numElementos[3] <- 4
	numElementos[4] <- 28
	numElementos[5] <- 3
	numElementos[6] <- 7
	numElementos[7] <- 12
	numElementos[8] <- 91
	numElementos[9] <- 19
	numElementos[9] <- 84

    
	maximo <- numElementos[1]
	minimo <- numElementos[1]

	Para contador<-1 Hasta totalBucle Hacer
		Si numElementos[contador]>maximo Entonces
			maximo <- numElementos[contador]
		FinSi
		Si numElementos[contador]<minimo Entonces
			minimo <- numElementos[contador]
		FinSi
	FinPara

	Escribir 'El número máximo es: ',maximo
	Escribir 'El número mínimo es: ',minimo
FinAlgoritmo
