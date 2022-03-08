inclua biblioteca Util --> util
	
	funcao inicio()
	{
		inteiro vetor [10]

		//preencher vetor
		para (inteiro posicao = 0;posicao < 10; posicao++ )
{
		vetor[posicao] = util.sorteia(0,100) //sorteia um número e atribui à posição do vetor
}

          //exibe o vetor na ordem original
          escreva ("vetor na ordem original:\n")

          para(inteiro posicao = 0; posicao < 10; posicao++)
          {
          	escreva (vetor[posicao], " ")
          }

          //exibe o vetor na ordem inversa
          escreva ("\n\nvetor na ordem inversa:\n")

          para(inteiro posicao = 9;posicao >=0;posicao--)
          {
          	escreva (vetor [posicao]," ")
          }
}
}
