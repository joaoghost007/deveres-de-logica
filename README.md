# deveres-de-logica
programa
{
	inclua biblioteca Matematica
	
	funcao inicio()
{
		
     real a,b,div
     a = 3.33
     b = 10.3
     div = b / a
     div = Matematica.arredondar (div,2)
     limpa ()
     escreva ("resultado da divisão entre a e b: ", div)
     
	}
}    

programa
{
	
   
    funcao inicio()
    {
    inteiro  contador
   

        para (contador = 100; contador>= 0; contador --){
            escreva(contador,"\n")
        }
    }
}

programa
{
	
	funcao inicio()
	{
		  inteiro opcao
    real pag , resultado, kg_livre=19.90 , kg_pesado=79.90, qpt ,peso=0.400
    
        escreva("menu p/ restaurante\n")
        escreva("1)kg_livre\n")
        escreva("2) kg_pesado\n")
      
           escreva("Informe a opção que Deseja")
           leia (opcao)

           limpa()

           escreva("informe o valor do pagamento em dinheiro:")
           leia(pag)

           escreva("informe a quantidade de pratos total:")
           leia(qpt)

           escreva("informe o peso do seu prato:")
           leia(peso)
           
            escolha (opcao)
        {
            caso 1:
            resultado= (peso*qpt*kg_livre)
            escreva("O Resultado da operação é:",resultado)
            pare
            caso 2:
            resultado= (peso*qpt*kg_pesado)
            escreva("O Resultado da operação é:",resultado)
            pare 
        }
	}
}

programa
{
	
	funcao inicio()
	{
		  inteiro opcao
    real saldo,saque,deposito,resultado
    
        
        escreva("1)saque\n")
        escreva("2)deposito \n")
      
           escreva("Informe a opção que Deseja")
           leia (opcao)

           limpa()
         
           escreva("informe o valor do saque em dinheiro:")
           leia(saque)

            escreva("informe o saldo da conta:")
           leia(saldo)
           
           escreva("informe o valor do deposito:")
           leia(deposito)

           
            escolha (opcao)
        {
            caso 1:
            resultado= (saldo-saque)
            escreva("O Resultado da operação é:",resultado)
            pare
            caso 2: 
            resultado= (saldo+deposito)
            escreva("O Resultado da operação é:",resultado)
            pare 
        }
	}
}

programa
{
	
	funcao inicio()
	{
	inteiro v1,v2,maior

	escreva("informe o primeiro valor:")
	leia(v1)
     escreva("informe o segundo valor:")
	leia(v2)

	limpa()

	se (v1>v2){
		escreva("o primeiro valor e o maior:",v1)
	}
		 senao 
		 	escreva("o segundo valor e o maior:",v2)
	}
}

programa
{

	
	funcao inicio()
	{
	real  custoFabrica, custoConsumidor, percentDistribuidor, percentImpostos

	escreva("Informe o custo de fabrica do carro:")
	leia(custoFabrica)

	percentDistribuidor = custoFabrica * 0.28
	percentImpostos = custoFabrica * 0.45
	custoConsumidor = custoFabrica + percentDistribuidor + percentImpostos 

	escreva("O custo final do consumidor é de R$", custoConsumidor)
	    
	}
}

programa
{
	inclua biblioteca Matematica
	
	funcao inicio()
{
		
     real a,b,div
     a = 3.33
     b = 10.3
     div = b / a
     div = Matematica.arredondar (div,2)
     limpa ()
     escreva ("resultado da divisão entre a e b: ", div)
     
	}
}
