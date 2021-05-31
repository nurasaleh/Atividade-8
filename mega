programa {

//trabalho feito por: 
//Ludmila Martins
//Nura Saleh	
    
    inclua biblioteca Util --> u
	funcao inicio() {
		
		inteiro numero
		inteiro aposta 
		inteiro op
		inteiro mega[15]
		inteiro quina[15]
		inteiro lotom[50]
		inteiro lotof[20]

     
          escreva("***** APOSTAS *****\n")
	     escreva("***********************\n")
	     escreva("*     1-Mega-Sena     *\n")
	     escreva("*     2-Quina         *\n")
	     escreva("*     3-Lotomania     *\n")
	     escreva("*     4-Lotofácil     *\n")
	     escreva("***********************\n")
		
		escreva ("digite o número correspondende a aposta que você gostaria de fazer: ")
		leia(op)
		
		escreva("quantas vezes você deseja jogar a mesma aposta: ")
		leia(aposta)
	            
		
		escolha (op){

			
		
		    caso 1:
			escreva ("quantas dezenas você deseja apostar? Lembrando que só podem ser de 6 a 15 dezenas: ")
			leia (numero)

			limpa()
			
			enquanto (numero <6 ou numero >15){
			escreva ("só podem ser apostados de 6 a 15 dezenas, por favor tente novamente: ")
			leia (numero)
			}
			 se (numero == 6){
			    escreva(" total de R$4,50.\n")
			}
			senao se (numero == 7){
			    escreva(" total de R$31,50.\n")
			}
			senao se (numero == 8){
			    escreva(" total de R$126,00.\n")
			}
			senao se (numero == 9){
			    escreva("  total de R$378,00.\n")
			}
			senao se (numero == 10){
			    escreva("total de R$945,00.\n")
			}
			senao se (numero == 11){
			    escreva(" total de R$2079,00.\n")
			}
			senao se (numero == 12){
			    escreva(" total de R$4158,00.\n")
			}
			senao se (numero == 13){
			    escreva(" total de R$7722,00.\n")
			}
			senao se (numero == 14){
			    escreva(" total de R$13513,50.\n")
			}
			senao se (numero == 15){
			    escreva(" total de R$22522,50.\n")
			}
			
		 
			
			inteiro sorteio
			logico rep = falso 
			
			para (inteiro j = 0; j < 15; j++){
			    faca {
			        sorteio = u.sorteia (1,60)
			        rep = falso
			        
			    para (inteiro k = 0; k < 15; k++){
			    se (sorteio == mega [k] ){
			    rep = verdadeiro
			    pare
			}
			    }
			    } enquanto (rep)
			    
			mega [j] = (sorteio)}
			
			para (inteiro j = 0; j < numero; j++){
			    escreva(mega [j], " - ")
			}
		
		
        		    
    		    
			escreva ("\n\n")
			
			pare
			

			caso 2:
			escreva ("quantas dezenas você deseja apostar? Lembrando que só podem ser de 5 a 15 dezenas: ")
			leia (numero)

			limpa()
			
			enquanto (numero <5 ou numero >15){
			escreva ("só podem ser apostados de 5 a 15 dezenas, por favor tente novamente: ")
			leia (numero)}
			 se (numero == 6){
			    escreva("total de R$4,50.\n")
			}
			senao se (numero == 7){
			    escreva(" total de R$31,50.\n")
			}
			senao se (numero == 8){
			    escreva(" total de R$126,00.\n")
			}
			senao se (numero == 9){
			    escreva(" total de R$378,00.\n")
			}
			senao se (numero == 10){
			    escreva(" total de R$945,00.\n")
			}
			senao se (numero == 11){
			    escreva(" total de R$2079,00.\n")
			}
			senao se (numero == 12){
			    escreva(" total de R$4158,00.\n")
			}
			senao se (numero == 13){
			    escreva(" total de R$7722,00.\n")
			}
			senao se (numero == 14){
			    escreva(" total de R$13513,50.\n")
			}
			senao se (numero == 15){
			    escreva(" total de R$22522,50.\n")
			}
	
			
			inteiro s
			logico r = falso 
			
			para (inteiro v = 0; v < 15; v++){
			    faca {
			       s = u.sorteia (1,60)
			       r = falso
			        
			    para (inteiro b = 0; b < 15; b++){
			    se (s == quina [b] ){
			    r = verdadeiro
			    pare
			}
			    }
			    } enquanto (r)
			    
			quina [v] = (s)}
			
			para (inteiro v =0 ; v < numero; v++){
			    escreva(quina [v], " - ")
			}
		
		
			escreva ("\n\n")
			
			pare

            

			caso 3:
			escreva(" na lotomania o número fixo de dezenas é 50 ")
			leia (numero)

			limpa()
			
			enquanto (numero <1 ou numero >50){
			escreva (" por favor tente novamente: ")
			leia (numero) }
			
		   
			
			inteiro s2
			logico repetir = falso 
			
			para (inteiro r = 0; r < 50; r++){
			    faca {
			       s2 = u.sorteia (1,60)
			       repetir = falso
			        
			    para (inteiro u = 0; u < 50; u++){
			    se (s2 == lotom [u ]){
			    repetir = verdadeiro
			    pare
			}
			    }
			    } enquanto (repetir)
			    
			lotom [r] = (s2)}
			
			para (inteiro r = 0; r < numero; r++){
			    escreva(lotom [r], " - " )
			}
		
			
			escreva (" total de R$2,50.")
			
			
			
			escreva ("\n\n")
			
			pare

			

			caso 4:
			escreva ("quantas dezenas vc deseja apostar? Lembrando que só podem ser de 15 a 20 dezenas: ")
			leia (numero)

			limpa()
			
			enquanto (numero <15 ou numero >20){
			escreva ("só podem ser apostados de 15 a 20 dezenas, por favor tente novamente: ")
			leia(numero)}
			
			
			se (numero == 15){
			    escreva(" total de R$2,50.\n")
			}
			senao se (numero == 16){
			    escreva(" total de R$40,00.\n")
			}
			senao se (numero == 17){
			    escreva("total de R$340,00.\n")
			}
			senao se (numero == 18){
			    escreva(" total de R$2040,00.\n")
			}
			senao se (numero == 19){
			    escreva(" total de R$9690,00.\n")
			}
			senao se (numero == 20){
			    escreva(" total de R$38760,00.\n")
			}
				 
			
			inteiro a
			logico b = falso 
			
			para (inteiro w = 0; w < 15; w++){
			    faca {
			       a = u.sorteia (1,60)
			       b = falso
			        
			    para (inteiro x = 0; x < 20; x++){
			    se (a == lotof [x] ){
			    b = verdadeiro
			    pare
			}
			    }
			    } enquanto (b)
			    
			lotof [w] = (a)}
			
			para (inteiro w = 0; w < numero; w++){
			    escreva(lotof [w], " - " )
			}
		
			
			
			escreva ("\n\n")
			
			pare
      }
				}
		
}
