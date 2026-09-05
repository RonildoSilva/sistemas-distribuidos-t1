# Sistemas Distribuídos: trabalho 1 (sockets)

> Exercícios de comunicação por sockets em Java: UDP, TCP, multicast, calculadora remota, chat bloqueante e não bloqueante (NIO) e servidor com múltiplos serviços.

![status](https://img.shields.io/badge/status-concluído-success) ![java](https://img.shields.io/badge/Java-8-blue) ![sockets](https://img.shields.io/badge/java.net%20%2B%20java.nio-sockets-lightgrey)

## Sobre
Trabalho 1 da disciplina de Sistemas Distribuídos (UFC Campus Quixadá, 2016, professor Paulo Rego), feito com Dieinison Jack. Parte dos códigos base vem do material do livro *Distributed Systems: Concepts and Design* (Coulouris et al.).

| Pacote | Questão |
|---|---|
| `q01` | Executar os exemplos de sockets UDP, TCP e multicast do livro |
| `q02` | Calculadora remota sobre UDP com as quatro operações; mensagem no formato `n1 op n2` |
| `q03` | Chat entre dois processos sobre TCP |
| `q04` | Chat não bloqueante com `java.nio` (`Selector`, `SocketChannel`) |
| `q05` | Segundo serviço no mesmo servidor: cifra/ordenação dos caracteres da mensagem |

## Como executar
```bash
javac -d bin $(find src -name "*.java")
java -cp bin ufc.cc.sd.q02.CalculadoraUDPServer   # e, em outro terminal, o cliente correspondente
```

## Status
Concluído. Trabalho acadêmico; não recebe manutenção.

## Autores
Ronildo Silva · ronildo.comp@gmail.com
Dieinison Jack
