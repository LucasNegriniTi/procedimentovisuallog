# procedimentovisuallog
Procedimento para esrtudo 
Algoritmo "Procedimento1"
// Disciplina   : [Linguagem e Lógica de Programação]
// Professor   : Antonio Carlos Nicolodi 
// Descrição   : Aqui você descreve o que o programa faz! (função)
// Autor(a)    : Nome do(a) aluno(a)
// Data atual  : 15/12/2025
Var
// Seção de Declarações das variáveis
   I: Inteiro
   N, Pesado: Caractere
   P, Mai: Real
   Procedimento Topo()
   inicio
         LimpaTela
         EscrevaL("--------------------")
         EscrevaL(" Detector de Peso")
         EscrevaL(" Maior Pesa Detectado até agora foi", Mai, "Kg")
         Escreval("---------------------------")
   FimProcedimento
Inicio
// Seção de Comandos, procedimento, funções, operadores, etc...
Topo ()
   Para I <- 1 ate 5 faca
        Escreva("Digite o nome:   ")
        Leia (N)
        Escreva("Digite o peso de ", N, ": ")
        Leia (P)
        Se (P>Mai) então
        Mai <- P
        Pesado <- N
        FimSe
        Topo()
   FimPara
          Topo()
   LimpaTela
     EscrevaL("A Pessoa mais pesada foi ", Pesado, ", com ", Mai, " Quilos ")



Fimalgoritmo
