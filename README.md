Super Trunfo - Países (em C)
Este é um projeto desenvolvido por mim como exercício prático de programação em linguagem C, com base no desafio Super Trunfo - Países. O objetivo foi construir um sistema de cadastro, exibição e comparação de cartas representando cidades fictícias, simulando uma versão simplificada do jogo Super Trunfo.

✨ Sobre o Projeto
O sistema permite cadastrar duas cartas, cada uma com dados de uma cidade. A ideia é que cada cidade pertença a um estado (representado por letras de A a H), formando códigos como A01, B02, etc. Para cada cidade, o programa coleta os seguintes atributos:

População (unsigned long int)

Área (float)

PIB (float)

Número de pontos turísticos (int)

Além disso, o programa calcula automaticamente dois indicadores:

Densidade Populacional = População / Área

PIB per Capita = PIB / População

E também realiza uma comparação entre as duas cidades, com base em cada atributo.

🔍 Funcionalidades Implementadas
Entrada de dados via terminal, utilizando scanf

Exibição organizada dos dados de cada carta, com printf

Cálculo automático de:

Densidade Populacional

PIB per Capita

Super Poder (soma de todos os atributos, com inverso da densidade populacional)

Comparação dos atributos entre as duas cartas:

Para Densidade Populacional, vence a cidade com menor valor

Para os demais atributos, vence a cidade com maior valor

Cada comparação exibe um resultado (1 = carta 1 vence, 0 = carta 2 vence)

⚙️ Restrições Técnicas
O desafio propôs restrições intencionais para estimular o raciocínio com base em lógica e tipos de dados:

Nenhum laço de repetição foi utilizado (for, while)

Nenhuma estrutura condicional foi utilizada (if, else)

Toda a lógica foi resolvida com expressões diretas

🛠 Tecnologias e Ferramentas
Linguagem: C

Editor: Visual Studio Code

Compilador: MinGW-w64 (via MSYS2) para Windows

💡 Aprendizados
Durante esse exercício, pude praticar conceitos essenciais da linguagem C:

Manipulação de diferentes tipos de dados

Entrada e saída padrão (scanf e printf)

Operações matemáticas com float e unsigned long int

Organização do código de forma clara e sequencial

Aplicação de lógica sem laços ou condicionais
