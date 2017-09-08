Algoritmo "numeroparimpar"

Var
    numero: inteiro

Inicio
    escreva ("numero inteiro")
    leia (numero)
    //verifique se o numero e positivo

    se numero >=0 entao
    //verificar se o numero e par ou impar
    se numero mod 2 = 0 entao
            escreva (" numero par , numero:", numero)
    senao
         escreva (" numero impar :" , numero)
    fimse
    senao
         escreva (" numero negativo , numero :" , numero)
    fimse
Fimalgoritmo