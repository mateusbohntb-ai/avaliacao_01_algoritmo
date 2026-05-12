# avaliacao_01_algoritmo


algoritmo "Primeiro Programa"

var
  opcao: inteiro
  mtr: matriz [1..10 , 1 .. 10 ] de caracter
  mtr2:matriz [1..10 , 1..10 ] de caractere
  mtr3:matriz [1..10 , 1..10 ] de caractere
  j , n : caractere

  mtr4 :matriz [1..10 ,1..10] de caractere
  acertos: matriz[1..10,1..10] de logico
  funcionario:caractere

inicio




  escreval ("Digite as seguintes opções ", " Opção 1 para cadastro de funcionario  "," Opção 2 para pesquisa de funcionarios "," Opção 3 exibir todos os funcionarios " ,"Opção 4 encerrar o programa")
  leia(opcao)




  se  opcao = 1 entao





    para j de 1 ate 10 passo 1 faca
      para n de 1 ate 10 passo 1  faca
        escreval("Qual nome dos funcionarios para cadastro ")
        leia (funcionario)
        mtr[j,n]<-funcionario

      fimpara
    fimpara



    para j de 1 ate 10 passo 1 faca
      para n de 1 ate 10 passo 1  faca
        escreval("Qual é o cargo dos funcionarios  ")
        leia (funcionario)
        mtr2 [j,n]<-funcionario

      fimpara
      escreval (" ")
    fimpara


    para j de 1 ate 10 passo 1 faca
      para n de 1 ate 10 passo 1  faca
        escreval("Qual é a data de admição do funcionario  ")
        leia (funcionario)
        mtr3 [j,n]<-funcionario

      fimpara
      escreval (" ")
    fimpara


    para j de 1 ate 10 passo 1 faca
      para n de 1 ate 10 passo 1 faca
        escreva( mtr2[j,n],mtr[j,n],mtr3[j,n])



      fimpara
      escreval (" ")
      escreval (" ")
      escreval (" ")
    fimpara




  senao se   opcao = 2 entao
    escreval ("Escreva o nome do funcionario que deseja pequisar ")

    leia (funcionario)

    se funcionario = "mateus" entao


      escreval("O cargo que ele está é pedreiro e seu nome é mateus.")


    senao   se funcionario=("") entao

      escreval(funcionario,"nao existente")

    fimse
  fimse

senao se opcao = 3 entao

 Escreva("Nao a funcionarios cadastrados ")
senao se opcao = 4 entao
  escreva("Fim do progrma ")




fimse
fimse
fimse
fimse
fimalgoritmo
