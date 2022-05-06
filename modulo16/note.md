# OPERADORES

## Aritméticos: Retornam o resultado de uma operação

+ Somar
- Subtrair
* Multiplicar
/ Dividir
% Módulo

## Comparadores matemáticos: Teste lógico, retorno booleano (true / false)

< menor que
> Maior que
<= menor ou igual
>= maior ou igual

## Comparadores lógicos: Teste lógico, retorno booleano (true / false)

== igualdade entre sentenças (valor)
!= diferença entre sentenças (valor)
=== igualdade entre sentenças (valor e tipo)
!== diferença entre sentenças (valor e tipo)

## Operadores de Lógica e Junção Lógica

!    NÃO (NOT)
&&   E (END)
||   OU (OR)

#### Exemplos

a != b       //O valor de a é diferente de b?
x !== y      //O valor e o tipo de x é diferente de y?
!a == b      //O valor de a não é igual ao valor de b?

#### As condições lógicas são convertidas em números binários

true é equivalente a 1
false é equivalente a 0

#### Operador lógico de atribuição

Tem a capacidade de atribuir valor a uma variável a partir de uma condição lógica.
Economiza IFs
Se for definir apenas o valor de uma variável, não precisa usar IF's.

##### Exemplos de interpretação do lógico por atribuição

let cor = "cinza"  //Estou dizendo que a variável cor é cinza.
let meu carro = cor == "preto" ? "preto" : "branco"  // A variável carro recebe o valor da variável cor. Se a variável carro tiver a cor preto, então, a cor do carro será preto, caso contrário, será branco. 


## Lembrete
-Para iniciar o node no terminal basta digitar node.
-Uso typeof para verificar o tipo da minha variável.
-Depois que eu declaro a variável com let, eu não preciso usar let novamente na variável.
-Função JavaScript toLowerCase() faz o falso ser verdadeiro e vice-versa.
    -Exemplo:
    -cor.toLowerCase() == "vermelho";

## IF
if(...){

}

## ELSE
else(...){

}

## ELSE IF
elseif(...){

}

## SWITCH
switch (cor){
    case 'branco':
        meuCarro = 'branco'
        break;
    case 'vermerlho':
        meuCarro = 'vermelho'
        break;
    default:
        console.log('Não temos nenhuma cor');
}

## Laços de Repetição
<p>Percorre um array, ou objeto javascript que tem mais de uma informação para trabalhar de forma repetida e controlada. <p>

### FOR

for([expressãoinicial]; [condição]; [incremento]{
    execução
}

while ([condição]){
    [execução]
}

do {
    [execução]
} while ([condição])

## Funções

<p>-Evitar a repetição de código</p>
<p>-Realizar chamadas dinâmicas de algoritmos</p>
