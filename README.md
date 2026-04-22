Cálculo de Números Primos - Programação Paralela (MPI)

Este repositório contém a implementação de dois programas para o cálculo de números primos utilizando a biblioteca MPI, abordando dois métodos diferentes de distribuição de tarefas paralelizadas:

- Naive: Implementação tradicional de cálculo de números primos, usando um algoritmo simples e ingênuo. Aqui, 10 combinações diferentes de envio e recepção de mensagens ponto a ponto são utilizadas para distribuir e coletar os resultados de forma paralela.
- Bag of Tasks: Implementação mais eficiente, onde as tarefas são distribuídas de forma dinâmica entre os processos, usando o conceito de "saco de tarefas". São exploradas 9 combinações de operações de envio/recebimento de mensagens para otimizar o desempenho da execução paralela.

Funcionalidades
  MPI_Send, MPI_Isend, MPI_Rsend, MPI_Bsend, MPI_Ssend.

Essas operações são combinadas com as funções de recepção de mensagens:
  MPI_Recv, MPI_Irecv.
