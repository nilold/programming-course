# programming-course

## Tópicos


### Parte 0
#### Introdução
- O que será ensinado (geral)
- Quem sou eu
- Porque Python


### Parte 1
#### Ambiente 1 (web)
- Google Colaboratory
- Jupyter Notebook
#### Estruturas de Dados
- Variáveis
- Tipos comuns: int, float, boolean
- Listas e Matrizes
- Strings
- ?Bytes (talvez seja desnecessário ensinar aqui)
- Dicionários
##### Revisão: Jogo da velha parte 1
- Definindo a matriz 3x3
- Coloando valor na matriz
- Lendo valor da matriz
#### Laços e Condições
- if/else
- for
- while
##### Revisão: Jogo da velha parte 2
- Verificando se uma casa está ocupada
- Listando casas vazias
- Verificando se alguma linha ganhou
- Verificando se alguma coluna ganhou (desafio)
#### Funções auxiliares
https://docs.python.org/3/library/functions.html
- print()
- len()
- sum()
- max()/min()
- all()/any()
- int()
- round()
- range()
- random() e randint()
##### Revisão: Jogo da velha parte 3
- Melhorando o teste de linhas usando all()
- Melhorando o teste de colunas usando all()
- Verificando se a diagonal direta ganhou usando range()
- Verificando se a diagonal reversa ganhou usando range() (desafio)
#### Desafio 1:
- "Printe" o tabuleiro


### Parte 2 - Criando scripts
#### Ambiente parte 2:
 - Instalando o Python
 - Instalando um editor
#### Argumentos e Entrada do usuário
- Criar, salvar e executar script
- sys.argv
- input()
##### Revisão: Jogo da velha parte 4
 - Obtenha o símbolo do usuário
 - Pergunte qual casa o usuário quer marcar
#### Funções
- Definição
- Parâmetros
- Cuidado!: Referência versus valor
##### Revisão: Jogo da velha parte 5
 - Criando a função que verifica casa livre
 - Criando função que lista casas livres
 - Criando a função de verificar linha
 - Criando as funções de verificar coluna, diagonal 1 e diagonal 2 (desafio)
 - Criando a função de verificar se alguém ganhou
#### PyPI - Não reinvente a roda
- O que é
- Instalando o pip
- Instalando o pytest
#### Testes de unidade - Parte 1
- Porque são importantes?
- TDD
- Criando uma função simples usando TDD
- Módulo de testes
##### Revisão: Jogo da velha parte 6
- Criando o módulo de testes
- Criar um teste para a função
- Refatorar a função "verifica_casa_livre"
- Criar um teste para função lista casas livres (desafio)
- Criar um teste para as funções de verificar linha, coluna e diagonais.
#### Testes de unidade- Parte 2
- Mock
##### Revisão: Jogo da velha parte 7
- Criar teste para verificar função de obter símbolo
- Criar teste para verificar função do usuário escolher a casa
- Criar um teste para a função de verificar se algum jogador venceu

### Parte 3 - POO
#### Classes
- Explicação geral
- Definindo uma classe: nome, atributos, funções
- Definindo métodos: self
- Instanciando objetos
