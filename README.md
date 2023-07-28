console.log('Hello world')
 let a = 1
 let b = 2
 let c = 3
 let d = '1'
 //Comparação de igualdade
 // = atribui valor, == comparacao de valor, === valor e tipo
 let valor = a == d
 console.log(valor)
let valortipo = a === d
console.log(valortipo)

//Maior
let maior = a > b
console.log(maior)

//maior = igual
let maior_igual = a >= b
console.log(maior_igual)

//maior e igual e mesmo tipo
let maior_igual_tipo = a >= b && typeof(a) === typeof(b)
console.log(maior_igual_tipo)
console.log(b)

//diferente
let diferente = a != b
console.log(diferente)

//valor e tipo diferente
let diferente_tipo = a !== d
console.log(diferente_tipo)

//Combinado
//E ou AND ou & ou &&
let operador_and = a < b && b < c // 1 < 2 e 4 < 3 seria falso
console.log(operador_and)

//OU ou OR ou | ou ||
let operador_or = a < b || b < c //1 < 2 e 2 < 3 daria verdadeiro basta um ser verdadeiro
console.log(operador_or)
 
function nota(nota){
    //se o aluno tirou a nota acima de 8 ele esta aprovado
    //caso contrario reprovado
    if(nota >= 8){
        return 'APROVADO'
    }else{
        return 'REPROVADO'
    }
}
console.log(nota(5))

