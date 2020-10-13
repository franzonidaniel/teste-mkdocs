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

```mermaid
graph TD
A[Client] --> B[Load Balancer]
B --> C[Server01]
B --> D[Server02]
```
