# Anotações 

## Escopo de programa 
- Importações (using)
- Namespace (divisão de pasta)
- Classe 
- Método Principal (Main)

## Variaveis
- Instanciar é criar(objeto)

> Utilizar ou não tipo(ou var)

> EU PREFIRO USAR SEMPRE TIPO!

> Coesão
> * Sempre usar bons nomes na variaveis!(coeso)
> * Sem caracteres na declaração
> * Não pode repetir o nome das variaveis
> * Sempre a primeira letra é minuscula

> Declaração:
> * tipo nome atribuição(=) valor;


## Constantes
* Uma vez o valor atribuido ele não é alterado

> Regra:
> * A declaração é igual a da variavel com o const antes
> * È obrigatorio sempre atribuir um valor na declaração
> * Todas as letras devem ser maiuculas separada por _


### Palavras resevadas(keywords)
![img](/anotacoes/palavras_resevadas.png)
* Existem mais!!!

### Comentarios
> Regra:
> - Uma linha //
> - Multiplas Linhas  /* */
> - Notação XML /// (Coloca um valor do funcionamento, é usado para classes!)

### System(Tipo Base do DotNET)
* Tudo herda dele
* Já é usado implicitamente
* Mas precisa declarar

## Tipos Primitivos(Tipos de Valor)
built-in types(São os padrões)

* byte(
    0 até 255 
) -> Não acho muito usado!
* sbyte (
    -128 até 127
) -> Não acho muito usado

> Números Inteiros
* u é sem sinal(Não recebe negativo)
* short(
    -32,768 até 32,767
)/ushort(
    0 até 65.535
)
* int(
    -2,147,483,648 até 2,147,483,647
    )/uint (
        0 até 4,294,967,295
    )
* long(
    -9,223,372,036,854,775,808 até 9,223,372,854,775,807
)/ulong(
    0 até 18,446,744,073,709,551,615
)

> Numeros Reais(Recebem Negativos)
* float (Notação F - Isso significa que para utilizar esse tipo tem que declarar o f no final do valor) (
    -3.402823e38 até 3.402823e38
)
* double (
    -1.79769313486232e308 até 1.79769313486232e308
)
* decimal (Notação M - Isso significa que para utilizar esse tipo tem que declarar o M no final do valor) (
    (+ ou -)1.0 c10e-28 ate 7.9 x 10e28
)

> Boolean - Verdadeiro ou Falso
* bool

> Char
* 1 Caracter - Não é muito usado!
> * É colocado em aspas simples 'A';

> String
* string também é um texto(Uma lista de caracter)
* Sempre com aspas duplas "texto"

> Var
* var (subistitui qualquer tipo, ele assume o tipo do primeiro item atribuido a ele!)