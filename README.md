# Compilador
O compilador é um projeto feito em JavaScript, ele tem como funcionalidade compilar uma pseudo linguagem de programação em Português em instruções capazes de serem enterpretados. A linguagem suporta comandos como loop, if, chamada de funções e de procedimentos, além de avaliar expressões matematicas utilizando pós-fixa.

##### Link para visualização - https://guipernicone.github.io/Compilador/

### Instruções
Todas as instruções que podem ser geradas apos a compilação de um codigo:
- LDC k (Carregar constante)
- LDV n (Carregar valor)
- ADD (Somar)
- SUB (Subtrair)
- MULT (Multiplicar)
- DIVI (Dividir)
- INV (Inverter sinal)
- AND (Conjunção)
- OR (Disjunção)
- NEG (Negação)
- CME (Comparar menor)
- CMA (Comparar maior)
- CEQ (Comparar igual)
- CDIF (Comparar desigual)
- CMEQ (Comparar menor ou igual)
- CMAQ (Comparar maior ou igual)
- START (Iniciar programa principal)
- HLT (Parar)
- STR n (Armazenar valor)
- JMP t (Desviar sempre)
- JMPF t (Desviar se falso)
- NULL (Nada) 
- RD (Leitura)
- PRN (Impressão)
- ALLOC m,n (Alocar memória)
- DALLOC m,n (Desalocar memória)
- CALL t (Chamar procedimento ou função)
- RETURN (Retornar de procedimento)

### Exemplo
```
programa exemplo:
  var x, y: integer;
  
  procedimento p;
  var z: integer;
  inicio
    z:= x; x:=x-1;
    se z>1 entao p
           senao y:=1;
    y:=y*z
  fim { p };
    
 inicio
   leia(x);
   p;
   escreva (y);
   escreva (x)
 fim. 
```
