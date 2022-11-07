programa
{
	inclua biblioteca Util	
	
	funcao inicio()
	{
		cadeia convidados[100]
		inteiro opcao = 99
		inteiro contadorConvidados = 0

		enquanto(opcao != 4){
			
			escreva("\n==========MENU==========\n")
		  	escreva("[ 1 ] Cadastrar convidado \n")
		  	escreva("[ 2 ] Listar convidados\n")
		  	escreva("[ 3 ] Remover convidado\n")
		  	escreva("[ 4 ] Sair\n")
		  	escreva("========================\n")
		  	
		  	escreva("Opção: ")
		  	leia(opcao)

			
			escolha(opcao){
				
				caso 1:
				cadeia convidado
				
				escreva("informe o nome do convidado: ")
				leia(convidado)

				convidados[contadorConvidados] = convidado
				contadorConvidados++
				
				pare

				caso 2: 

					para(inteiro i=0; i < 100; i++){

						se(convidados[i] != ""){
							escreva(i+1," -> ",convidados[i], "\n")
						}						
					}
					
				pare

				caso 3: 
					cadeia convidadoParaRemover

					escreva("Qual o convidado a ser removido? ")
					leia(convidadoParaRemover)

					para(inteiro i=0; i < 100; i++){

						se(convidados[i] == convidadoParaRemover){
							convidados[i] = ""
							pare
						}
					}
				pare

				caso 4:
					escreva("Obrigado por usar nosso sistema!\n")
					Util.aguarde(3000)
				pare
				
				caso contrario: escreva("contrario")
				pare
			}

			//limpa()
		}
	}
}
