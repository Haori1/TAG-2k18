Instruções para Compilação:

    Entre na pasta em que a pasta deste trabalho se encontra, usando o comando "cd";
    Se estiver no windows basta executar "mingw32-make.exe" e depois ".\exec.exe";
    Se estiver no Linux bastar executar "make" e depois "./exec".

Obs.: Caso nao tenha o mingw32-make.exe instalado faça:
    g++ -c src/*.cc
    g++ -o exec *.o -Wall -pedantic -g
    .\exec.exe

A documentação foi feita no doxygen e encontra-se na pasta html.
