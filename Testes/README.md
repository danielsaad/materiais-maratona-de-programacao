# Instruções para Testes nos Laboratórios de Informática

Abaixo seguem instruções de programas minimalistas que visam a verificação do ambiente mínimo de desenvolvimento para a realização de Maratonas de Programação.

## Teste do Compilador C

Compile o programa com o `gcc` e em seguida, execute o binário gerado.

```bash
gcc teste.c -o testeC
./testeC
```

## Teste do Compilador C++

Verifique a versão do `g++` com o comando:

```bash
g++ --version
```

Ela deve estar igual ou superior a  `4.8`.


Compile o programa com o `g++` e em seguida, execute o binário gerado:

```bash
g++ -std=c++11 teste.cpp -o testCPP
./testCPP
```

## Teste do Interpretador Python2


Primeiramente, verifique se o interpretador `python2` tem versão igual ou superior a `2.7` e está instalado.

```bash
python2 --version # Ou python --version
```

Para interpretar o programa denominado `teste.py`, basta executar:

```bash
python2 teste.py # Ou python teste.py
```



## Teste do Interpretador Python3


Primeiramente, verifique se o interpretador `python3` tem versão igual ou superior a `3.6` e está instalado.

```bash
python3 --version # Ou python --version
```

Para interpretar o programa denominado `teste.py3`, basta executar:

```bash
python3 teste.py3 # Ou python teste.py3
```
## Teste da Máquina Virtual Java

Verifique a versão do `Java`e do `javac` a partir dos seguintes comandos:

```bash
java --version
javac --version
```

É interessante que o Java 8 ou superior este


## Verificação das IDEs

### Eclipse 
Verifique se o eclipse está instalado e certifique que é a versão eclipse oxygen ou superior.

Após a abertura do eclipse, crie um novo projeto java.

Após a criação do novo projeto, crie um arquivo classe chamado 'Main.java'.

Insira o seguinte código:

```java
public class Main {

    public static void main(String[] args) {
        System.out.println("Hello, World");
    }

}
```

Aperte play. Ele deve imprimir no console do eclipse.


### Outras IDEs

Verifique se as seguintes IDEs abrem normalmente sem problema.

- Sublime
- Visual Code
- geany
- Codeblocks
- vim (linha de comando)
- PyCharm

Se alguma delas não estiver instalada, será necessário requisitar a instalação das mesmas para o responsável pelo laboratório.




