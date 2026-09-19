
# Scanner de Portas TCP em Python
O scanner deve ser utilizado apenas em computadores, redes e sistemas que você possui ou para os quais possui autorização para realizar testes.
[untitled1.py](https://github.com/user-attachments/files/32407367/untitled1.py)

Projeto simples desenvolvido em Python para praticar conceitos básicos de redes e Cibersegurança.

## Sobre o projeto

O programa realiza uma verificação de portas TCP em um endereço IP informado e identifica quais portas estão abertas.

Por padrão, o projeto utiliza:

```text
127.0.0.1
```

que representa o próprio computador.

## Tecnologias utilizadas

* Python
* Socket
* TCP/IP

## Funcionamento

O programa utiliza a biblioteca `socket` do Python para tentar estabelecer uma conexão com cada porta.

Exemplo:

```python
portas = range(80, 101)
```

Nesse caso, são verificadas as portas de 80 até 100.

## Objetivo

Projeto desenvolvido para fins educacionais, com o objetivo de praticar:

* Python
* Redes de computadores
* Portas TCP
* Sockets
* Conceitos básicos de Cibersegurança

## Uso responsável




