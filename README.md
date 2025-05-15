📘 Documentação do Projeto
Super Trunfo: Cidades do Mundo 🌍 (em C)
📌 Visão Geral
O Super Trunfo: Cidades do Mundo é um projeto em linguagem C, desenvolvido para simular a fase de cadastro de cartas de um jogo no estilo Super Trunfo. Cada carta representa uma cidade com atributos como população, PIB, área, pontos turísticos e informações derivadas como densidade populacional e PIB per capita.

🎯 Objetivos
Simular o cadastro e exibição de cartas de cidades

Calcular atributos estratégicos derivados automaticamente

Criar uma interface de terminal amigável e interativa

Modularizar o código em múltiplos arquivos (main, .h, .c)

Servir como base para funcionalidades futuras como batalhas ou persistência

📂 Estrutura do Projeto
less
Copiar
Editar
super_trunfo/
├── main.c         // Interface e controle do menu
├── cartas.c       // Funções de lógica (cadastrar, exibir, calcular)
├── cartas.h       // Definição das estruturas e protótipos
└── README.md      // Documentação do projeto
🛠️ Tecnologias
Linguagem: C

Terminal: Shell/CLI

Sistema: Compatível com Linux, macOS ou Windows (com MinGW ou WSL)

🔧 Como Compilar e Executar
Linux/macOS:
bash
Copiar
Editar
gcc main.c cartas.c -o super_trunfo
./super_trunfo
Windows (com MinGW):
bash
Copiar
Editar
gcc main.c cartas.c -o super_trunfo.exe
super_trunfo.exe
🖥️ Funcionalidades
✅ Cadastro de Cartas
Cada carta possui os seguintes campos:

Atributo	Tipo	Descrição
Estado	char[50]	Estado da cidade
Código da cidade	int	Código identificador da cidade
Nome da cidade	char[50]	Nome completo
População	long	Número total de habitantes
PIB	double	Produto Interno Bruto (em bilhões)
Área	double	Área territorial (em km²)
Pontos turísticos	int	Quantidade de atrações conhecidas
Densidade populacional	double	Calculado automaticamente (hab/km²)
PIB per capita	double	Calculado automaticamente (R$/habitante)

✅ Menu Interativo no Terminal
markdown
Copiar
Editar
=====================================
     SUPER TRUNFO - CIDADES DO MUNDO
=====================================
[1] Cadastrar nova carta
[2] Exibir todas as cartas
[0] Sair
-------------------------------------
🔢 Cálculos Derivados
Densidade Populacional:

densidade
=
popula
c
¸
a
˜
o
a
ˊ
rea
densidade= 
a
ˊ
 rea
popula 
c
¸
​
  
a
˜
 o
​
 
PIB per capita:

PIB per capita
=
PIB
popula
c
¸
a
˜
o
PIB per capita= 
popula 
c
¸
​
  
a
˜
 o
PIB
​
 
📈 Exemplos de Uso
Cadastro de cidade:

txt
Copiar
Editar
Estado: São Paulo
Código: 3550308
Nome: São Paulo
População: 12000000
PIB: 830.0
Área: 1521
Pontos turísticos: 15
Saída gerada:

yaml
Copiar
Editar
Cidade: São Paulo (São Paulo)
Código: 3550308
População: 12000000
PIB: 830.00 bilhões
Área: 1521.00 km²
Pontos Turísticos: 15
Densidade Populacional: 7885.61 hab/km²
PIB per capita: 69166.67
🚀 Expansões Futuras
 Sistema de batalhas (comparação de atributos)

 Salvamento em arquivos (modo histórico)

 Carregamento automático de cartas

 Interface gráfica (modo visual)

 Versão em C++ com OOP

🧠 Aprendizados
Este projeto reforça habilidades como:

Estruturação modular com .h e .c

Entrada e saída formatadas

Lógica de cálculos derivados

Uso de ANSI codes para estilização de terminal

Organização de menus e boas práticas

🤝 Contribuição
Sinta-se à vontade para sugerir melhorias, abrir issues ou forks!

👤 Autor
Maycon — Analista de Observabilidade | Foco em Cloud, DevOps e Engenharia
