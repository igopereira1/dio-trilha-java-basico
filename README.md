# Desafio ContaBanco

Este projeto foi desenvolvido como parte do curso de Java Básico oferecido pela Digital Innovation One (DIO). O objetivo do projeto é exercitar os conceitos básicos da linguagem Java, especialmente em relação à sintaxe, entrada de dados pelo terminal e manipulação de strings.

## Descrição

O projeto ContaBanco consiste em um programa Java que permite ao usuário inserir informações sobre uma conta bancária através do terminal. Após a inserção dos dados, o programa exibe uma mensagem de agradecimento ao usuário, mostrando os detalhes da conta que foram fornecidos.

## Funcionalidades

- Solicita ao usuário as seguintes informações sobre a conta bancária:
    - Número da conta
    - Agência
    - Nome do cliente
    - Saldo inicial
- Exibe uma mensagem de confirmação com os dados fornecidos pelo usuário.

## Como usar

1. Clone este repositório:
```bash
git@github.com:igopereira1/dio-trilha-java-basico.git
```
2. Navegue até o diretório do projeto:
```bash
cd ContaBanco
```

3. Compile o programa: certifique-se de ter o JDK (Java Development Kit) instalado em seu sistema.
```bash
javac src/main/java/ContaTerminal.java
```

4. Execute definindo o `classpath`:
```bash
java -cp src/main/java ContaTerminal
```

5. Ou navegando diretamente ao caminho onde está o arquivo .class:
```bash
cd src/main/java
java ContaTerminal
```

# Desafio Controle de Fluxo

Este projeto foi desenvolvido como parte da trilha de Java Básico oferecida pela Digital Innovation One (DIO). O objetivo deste desafio é exercitar todo o conteúdo apresentado no módulo de Controle de Fluxo, codificando um cenário específico.

## Descrição

O sistema deverá receber dois parâmetros via terminal que representarão dois números inteiros. Com esses dois números, o programa irá calcular a quantidade de iterações (utilizando um loop `for`) e realizar a impressão no console dos números incrementados.

Por exemplo, se forem passados os números 12 e 30, teremos uma iteração (for) com 18 ocorrências para imprimir os números, como por exemplo: "Imprimindo o número 1", "Imprimindo o número 2" e assim por diante.

Se o primeiro parâmetro for MAIOR que o segundo parâmetro, o programa lançará uma exceção customizada chamada ParametrosInvalidosException com a mensagem: "O segundo parâmetro deve ser maior que o primeiro".

## Como usar

1. Clone este repositório:
```bash
git clone https://github.com/dio-me/DesafioControleFluxo.git
```

2. Navegue até o diretório do projeto:
```bash
cd DesafioControleFluxo
```

3. Compile o programa: certifique-se de ter o JDK (Java Development Kit) instalado em seu sistema.
```bash
javac src/main/java/Contador.java src/main/java/ParametrosInvalidosException.java
```

4. Execute definindo o `classpath`:
```bash
java -cp src/main/java Contador
```

5. Ou navegando diretamente ao caminho onde está o arquivo .class:
```bash
cd src/main/java
java Contador
```
