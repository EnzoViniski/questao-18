Algoritmo "PA"

var
   n1, n2, n3, n4, pa, soma: real

inicio
   //Entrada de dados
   escreva("Digite o valor inicial: ")
   leia(n1)

   escreva("Digite a razão: ")
   leia(n2)

   escreva("Digite a quantidade de números: ")
   leia(n3)

   //Operações
   se n3 < 0 entao
      escreva("NÚMERO INVÁLIDO. ESCOLHA UM NÚMERO MAIOR QUE ZERO")
   senao
         n4 <- 0
         n3 <- n3 +1
      enquanto (n3 > 0) faca
         soma <- pa + n1
         n1 <- soma
         pa <- ((n3 - 1) * n4)
         n3 <- n3 - 1
         n4 <- n2
      fimenquanto
      escreva(soma)
   fimse

fimalgoritmo
