# Trabalho de Threads Periódicas

- Neste trabalho foi realizada a implementação de um algoritmo de threads periódicas em C++ com o intuito de analisar seu comportamento

## Guia de Instalação:
1. Extrair o arquivo zip para o local desejado
2. Crie um arquivo de entrada do tipo .txt e insira no diretório base do projeto (junto ao Makefile)
3. Comando ```make``` para compilar
4. Para executar ```make run```
5. Caso deseje recompilar, utilize ```make clean``` para apagar os objetos e repita os passos anteriores pra recriá-los
6. Caso tenha interesse, utilizando ```make valgrind``` o programa realizará a checagem de vazamento de memória

## Pré-requisitos: 
1. Bibliotecas Utilizadas
	- iostream
	- string
	- time.h
	- sched.h
	- signal.h
2. Sistema operacional: Linux 20.04
3. IDE : Visual Studio Code
4. Compilador: G++ 
5. Dialeto == C++17

## Autoria e constribuições:
- Esse projeto é autoria de Pedro Henrique Melo Araujo e Arthur Haickel Nina.
	
## Fontes:
- GRACIOLI, G., Notas de Aula. 2021.
- Clocks and Timers, University of Hamburg, c2022. Dispobnível em: https://www3.physnet.uni-hamburg.de/physnet/Tru64-Unix/HTML/APS33DTE/DOCU_007.HTM . Acesso em: 10 de fevereiro de 2022.
- Ngo, V. C., Implement Real-time Periodic Task for RTOS using Timers. 2020. Disponível em: https://channgo2203.github.io/rt_periodic\_task/ . Acesso em: 10 de fevereiro de 2022.
- <sched.h>, The Open Group, c1997. Disponível em: https://pubs.opengroup.org/onlinepubs/7908799/xsh/sched.h.html . Acesso em: 10 de fevereiro de 2022.
