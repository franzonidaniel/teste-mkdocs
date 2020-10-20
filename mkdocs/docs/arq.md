# Arquitetura
## Diagrama
![Diagrama](img/diagrama_1.png)
*Acima: Diagrama da Arquitetura*

## Tabela de Funções

Elemento     | Função        | Descrição
:----------- |:-------------:|:-----------:
MySQL        | Center        | Right
DropBox      | Center        | Right
Search engine| Center        | Right

## Grafo

``` mermaid
graph TD
A[Client] --> B[Load Balancer]
B --> C[Server01]
B --> D[Server02]
```
## Grafo 2

``` mermaid
sequenceDiagram
participant Alice
participant Bob
Alice->>John: Hello John, how are you?
loop Healthcheck
    John->>John: Fight against hypochondria
end
Note right of John: Rational thoughts <br/>prevail!
John-->>Alice: Great!
John->>Bob: How about you?
Bob-->>John: Jolly good!
```

## Grafo 3

``` mermaid
gitGraph:
options
{
    "nodeSpacing": 150,
    "nodeRadius": 10
}
end
commit
branch newbranch
checkout newbranch
commit
commit
checkout master
commit
commit
merge newbranch
```

## Pie Chart using Mermaid


``` mermaid
pie title Commits to mxgraph2 on GitHub
	"Sunday" : 4
	"Monday" : 5
	"Tuesday" : 7
  "Wednesday" : 3
```