# Sistema de Manipulação de Vetores em Java

Projeto desenvolvido em Java com funcionalidades de manipulação, ordenação, busca e testes automatizados utilizando JUnit.

---

# 📌 Funcionalidades

O sistema permite:

- Ordenar listas utilizando:
  - Bubble Sort
  - Selection Sort
  - Insertion Sort
- Verificar se o vetor está ordenado
- Realizar busca binária
- Informar:
  - Maior valor do vetor
  - Menor valor do vetor
- Trocar posições de elementos
- Multiplicar todos os valores do vetor
- Imprimir o vetor atual
- Executar testes automatizados com JUnit

---

# 🖥️ Menu do Sistema

```text
1) Ordenar lista
2) Verificar se a lista está ordenada
3) Realizar busca binária
4) Realizar testes no programa
5) Informar o maior valor da lista
6) Informar o menor valor da lista
7) Trocar a posição de 2 valores da lista
8) Multiplicar valores da lista
9) Imprimir lista
0) Sair
```

---

# 🧠 Conceitos Aplicados

Este projeto utiliza conceitos como:

- Programação Orientada a Objetos (POO)
- Estruturas de repetição
- Estruturas condicionais
- Vetores
- Métodos
- Classes e objetos
- Algoritmos de ordenação
- Busca binária
- Manipulação de arrays
- Testes automatizados com JUnit

---

# 📂 Estrutura do Projeto

```text
📦 projeto
 ┣ 📜 ListaManipulator.java
 ┣ 📜 Main.java
 ┣ 📜 TestJunit.java
 ┣ 📜 TestRunner.java
 ┗ 📜 Utilitarios.java
```

---

# 📄 Descrição das Classes

| Classe | Responsabilidade |
|---|---|
| `Main` | Interface principal e menu do sistema |
| `ListaManipulator` | Métodos de ordenação e busca binária |
| `Utilitarios` | Funções auxiliares para manipulação do vetor |
| `TestJunit` | Testes automatizados utilizando JUnit |
| `TestRunner` | Responsável por executar os testes |

---

# ✅ Testes Implementados

A classe `TestJunit` contém testes automatizados para:

## Métodos de Ordenação

- `bubbleSort()`
- `selectionSort()`
- `insertionSort()`

## Busca Binária

- Valor encontrado
- Valor não encontrado
- Vetor não ordenado

## Métodos Utilitários

- `trocarValores()`
- `multiplicarVetor()`
- `verificarOrdenado()`
- `maiorValor()`
- `menorValor()`

---

# ▶️ Como Executar

## Pré-requisitos

- Java JDK 8 ou superior
- JUnit 4

---

## Compilar o Projeto

```bash
javac *.java
```

---

## Executar o Sistema

```bash
java Main
```

---

# 🧪 Executar os Testes

Caso utilize JUnit 4:

```bash
java TestRunner
```

Ou diretamente pelo ambiente de desenvolvimento (Eclipse, IntelliJ ou VSCode).

---

# 📋 Exemplo de Vetor Utilizado

```java
int[] vetor = {64, 34, 25, 12, 22, 11, 90};
```

---

# 🔎 Exemplo de Funcionalidades

## Ordenação

O usuário pode escolher entre diferentes algoritmos de ordenação para organizar o vetor em ordem crescente.

---

## Busca Binária

A busca binária somente pode ser realizada quando o vetor estiver ordenado.

---

## Troca de Valores

Permite trocar os elementos de duas posições informadas pelo usuário.

---

## Multiplicação do Vetor

Multiplica todos os valores do vetor por um número informado.

---

# 🛠️ Tecnologias Utilizadas

- Java
- JUnit 4

---

# 📚 Objetivo do Projeto

Este projeto foi desenvolvido com fins educacionais para praticar:

- Algoritmos clássicos
- Estruturas de dados básicas
- Programação Orientada a Objetos
- Organização de código em Java
- Modularização
- Testes automatizados

---

# 👨‍💻 Autor

Paulo Ricardo Tebet Lyrio

- GitHub: https://github.com/Paulouuul
- LinkedIn: https://www.linkedin.com/in/paulo-ricardo-tebet-lyrio-8258b619b/
