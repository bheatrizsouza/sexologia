#hentai
aaaaaaaaaaaaaaaaaaaaaaaa
Algoritmo "alvaroquefez"
//  
//  
// Disciplina   : [Linguagem e Lógica de Programação]
// Professor   : Antonio Carlos Nicolodi 
// Descrição   : Aqui você descreve o que o programa faz! (função)
// Autor(a)    : Nome do(a) aluno(a)
// Data atual  : 01/08/2023
Var
   distancia: real
   preco: real

Inicio
   escreval("Que distancia você deseja percorrer? (em KM):")
   leia(distancia)

   se distancia <= 200 entao
      preco <- distancia * 0.50
   senao
      preco <- distancia * 0.45
   fimse

   escreval("preço total da passagem: R$", preco)

FimAlgoritmo
