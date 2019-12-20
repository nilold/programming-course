# Introdução à Programação com Python

## Tópicos


### Parte 0
#### Introdução
- O que será ensinado (geral)
- Quem sou eu
- A questão do inglês
- Porque Python


### Parte 1
#### Ambiente 1 (web)
- Google Colab
- Jupyter Notebook
#### Estruturas de Dados
- Variáveis
- Tipos comuns: int, float, boolean, strings
- Listas e Matrizes
- Dicionários
##### Revisão: Jogo da velha parte 1
- Definindo a matriz 3x3
- Lendo valor da matriz
- Colocando valor na matriz
#### Laços e Condições
- if/else
- for
- while
##### Revisão: Jogo da velha parte 2
- Verificando se uma casa está ocupada
- Listando casas vazias
- Verificando se alguma linha ganhou
- Verificando se alguma coluna ganhou (desafio)
#### Funções auxiliares (built in)
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
- Criar um teste para a função de printar tabuleiro
#### Testes de unidade- Parte 2
- Mock
##### Revisão: Jogo da velha parte 7
- Criar teste para verificar função de obter símbolo
- Criar teste para verificar função do usuário escolher a casa
- Criar um teste para a função de verificar se algum jogador venceu
#### Desafio 2:
- Refatore suas funções!

### Parte 3 - POO
#### Classes
- Explicação geral
- Definindo uma classe: nome, atributos, funções
- Definindo métodos: self
- Instanciando objetos
##### Revisão: Jogo da velha parte 8
- Criando a classe TicTacToe (tabuleiro hard-coded)
- Criando os méotodos (TDD)
- Instanciando um objeto e interagindo com ele
#### Dunder methods
- Método __init__()
- Método __repr__()
- Método __str__()
- Método __getitem__()
##### Revisão: Jogo da velha parte 9
- Criando o método __init__ (TDD)
- Criando o método __repr__ (TDD)
- Criando o método __str__ (TDD)
- Criando o método __getitem__ (TDD)
#### Herança
- Herança simples
- Herança múltipla (mixins)
##### Revisão: Jogo da velha parte 10
- Criando a classe Board: __init__(size), __getitem__()
- Fazer a classe TicTacToe herdar Board (TDD)
- Criando uma classe Chezz que herda Board
#### Abstrações e Protocolos (Interfaces)
- Métodos abstratos
- Classes abstratas
- Protocolos: duck typing
- ABCs
##### Revisão: Jogo da velha parte 11
- Criando a classe abstrata Game
- Método abstrato: start_game()
- Método abstrato: restart_game()
- Método abstrato: finish_game()
- Fazer a classe TicTacToe herdar Game (TDD)

### Parte 4 - Conclusão
#### Considerações finais
- O que fizemos
- Diferenças entre linguagens
- Continue praticando: cursos onlines
#### O que vem depois?
- Programação para Web (falar do curso do Zero à Implantação)
 - Frontend vs Backend
 - Devops
- Ciência e Engenharia de Dados
- Programação de aplicativos
- Programação gráfica (ex: Processing)
- Games (ex: Unity)
- Microcontroladores e robótica
