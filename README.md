# Problema de Busca em um Labirinto Utilizando Algoritmo A*

## Participantes
- [Aline Martins Dias (Aluno)](https://github.com/aline-m-dias)
- [Daniele Cristina Almeida (Aluno)](https://github.com/8dani)
-  [Gustavo Estevam Sena (Aluno)](https://github.com/Gultes)
- Talles Henrique de Medeiros (Orientador)

## Objetivos
- Aplicar os conhecimentos da Busca Informada para resolver um problema de Busca em Labirinto, de forma ótima utilizando uma heurística admissível.
- Realizar testes alterando o valor de de w - peso associado a heurística, de forma a verificar quando o Algoritmo A* irá começar a falhar.
- Reforçar o aprendizado sobre os algoritimos de Busca Informada.

## Sobre
O trabalho consiste em resolver o problema de busca em um labirinto utilizando uma Função de Avaliação (f(n) = g(n) + wh(n)) para gerenciamento  de Fronteira, seguido de seu uso no Algoritmo A* sobre o arquivo labirinto.py, um projeto inicial foi disponilizado pelo orientador, contendo a criação do labirinto e resolução utilizando Busca Não Informada (Busca em Profundidade e Busca em Largura)

## Run 🏃‍

```
# Clone este repositório
$ git clone https://github.com/aline-m-dias/trabalhoIA.git

$Com python 3 instalado na máquina:

# Abra uma IDE - Por exemplo - Visual Studio Code
# Instale a Python Imaging Library através do comando via terminal: pip install Pillow
# Acesse o diretório do projeto via comando - Ex:cd D:\trabalhoIA

# Digite no terminal
$ Python labirinto.py complexlab2.py

````
A execução irá retornar em Debug Console a seguinte resposta:

Qual algoritmo  de busca deseja utilizar para encontrar a solução do labirinto?

            MENU:

            [1] - Algoritmo de Busca em Largura
            [2] - Algoritmo de Busca em Profundidade
            [3] - Algoritmo de Busca A Estrela

````
Escolha uma opção: 3
Solucionando...
Busca em A*
Para peso [w em f(n) = g(n) + wh(n)]:  1
Tempo de Execução:  0.45871639251708984
Custo do Caminho; 123
Estados Explorados: 998
Solução:

````
![image](https://user-images.githubusercontent.com/72038613/189541570-493f87e8-958c-4811-818b-1dcec5a059f3.png)
````

````
Obs: De forma automática, quando a opção de resolução escolhida for Busca em A*, também serão gerados resultados para os pesoh = [1, 1.1, 1.2, 1.5, 1.6, 2, 2.5, 4, 5, 8, 10, 20]


