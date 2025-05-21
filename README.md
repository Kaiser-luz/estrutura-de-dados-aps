Sistema de Estruturas de Dados em C#
 Descrição do Projeto
Este projeto é um sistema de console em C# que apresenta menus interativos para trabalhar com diferentes estruturas de dados, como:

Vetores (Listas de inteiros)

Matrizes

Listas (Listas genéricas)

Filas (Queue)

Pilhas (Stack)

Algoritmos de Pesquisa (Linear e Binária)

É ideal para fins educacionais, permitindo que usuários explorem o funcionamento de estruturas básicas de dados e técnicas de busca.

 Como Rodar o Sistema
Passo a passo:
Clone ou baixe o repositório:

bash
Copiar
Editar
git clone https://github.com/seu-usuario/seu-repositorio.git
Abra o projeto em um editor de C#, como o Visual Studio ou Visual Studio Code com a extensão C#.

Compile e execute o programa:

Se estiver usando o terminal:

bash
Copiar
Editar
dotnet run
Ou use o botão "Iniciar" dentro do Visual Studio.

 Pré-requisitos
.NET SDK 6.0 ou superior

Sistema operacional compatível (Windows, macOS ou Linux)

Editor de código recomendado: Visual Studio / VS Code

 Exemplos de Uso
Inserir elementos em uma lista:

css
Copiar
Editar
Menu Principal → 3. Lista → 1. Inserir elemento
Remover item de uma fila:

css
Copiar
Editar
Menu Principal → 4. Fila → 2. Remover elemento
Pesquisar um valor usando busca binária:

css
Copiar
Editar
Menu Principal → 6. Algoritmos de Pesquisa → 2. Pesquisa Binária
 Estrutura do Menu
Menu Principal
text
Copiar
Editar
1. Vetores
2. Matrizes
3. Lista
4. Fila
5. Pilha
6. Algoritmos de Pesquisa
7. Sair
Submenus disponíveis
1. Vetores (List<int>)
Inserir elemento

Remover último elemento

Exibir todos os elementos

Buscar elemento

2. Matrizes
Inserir em posição específica

Remover (zera a posição)

Exibir matriz

Buscar elemento

3. Lista (List<string>)
Inserir elemento

Remover primeiro elemento

Exibir elementos

Buscar elemento

4. Fila (Queue<string>)
Inserir elemento

Remover primeiro elemento (FIFO)

Exibir elementos

Buscar elemento

5. Pilha (Stack<string>)
Inserir elemento

Remover topo da pilha (LIFO)

Exibir elementos

Buscar elemento

6. Algoritmos de Pesquisa
Pesquisa Linear

Pesquisa Binária (requer lista ordenada)
