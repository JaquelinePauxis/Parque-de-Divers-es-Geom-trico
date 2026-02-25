## 🏗 Projeto MEE  — Parque de Diversões Geométrico
✅ Comandos principais ( FASE 1 A 4)

ajuda → mostra lista de comandos do parque 

💬 quadrado <lado> → constrói um quadrado
Ex: quadrado 8

💬 retangulo <largura> <altura> → constrói um retângulo
Ex: retangulo 12 6

💬 trianguloreto <base> → triângulo retângulo em grid (perfeito)
Ex: trianguloreto 8

💬 triangulo <lado> → triângulo “equilátero aproximado” (visual)
Ex: triangulo 6

💬 circulo <raio> → círculo contorno
Ex: circulo 10

💬 disco <raio> → círculo preenchido
Ex: disco 7

✅ Fase 5 (montanha-russa)

estacao <largura> <comprimento> → cria estação (piso + trilho central)
Ex: estacao 8 10

trilhoReto <n> → trilho reto
Ex: trilhoReto 12

curvaDireita <n> → curva direita
Ex: curvaDireita 6

curvaEsquerda <n> → curva esquerda
Ex: curvaEsquerda 6

subida <n> → rampa de subida (com suporte)
Ex: subida 8

descida <n> → rampa de descida
Ex: descida 8

montanha 1 → monta percurso pronto completo (roteiro automático)

## 🎮 Guia do Aluno — O que cada fase faz

Neste projeto, você vai usar o Agent do Minecraft como um robô construtor.
Você não constrói com as mãos — você programa.
Cada fase ensina um conceito diferente de programação e matemática.

## 🔵 Fase 1 — Quadrado
Comando:
quadrado 8
O que acontece?

O Agent constrói um quadrado com o tamanho que você escolher.

Se você digitar quadrado 8, ele vai:
Andar 8 blocos
Virar 90°
Repetir isso 4 vezes

O que você está aprendendo:
Repetição (loop)
Ângulo de 90°
Como dividir um problema grande em partes menores
Você está ensinando o robô a repetir uma ação várias vezes.

## 🟢 Fase 2 — Retângulo
Comando:
retangulo 12 6
O que acontece?

O Agent constrói um retângulo com:
12 blocos de largura
6 blocos de altura

Ele alterna:
Lado maior
Lado menor
Lado maior
Lado menor

O que você está aprendendo:
Trabalhar com dois parâmetros
Alternar medidas diferentes
Entender largura e altura
Aqui você começa a controlar dimensões.

## 🟡 Fase 3 — Triângulos
3A — Triângulo Retângulo
trianguloreto 8

O Agent constrói:
Base
Lado vertical
Diagonal em “escadinha”

O que você aprende:
Como criar uma forma usando partes diferentes
Como funciona uma diagonal no mundo de blocos

## 3B — Triângulo Equilátero (aproximado)
triangulo 6

O Agent tenta simular um giro de 120° usando ajustes no grid.
O que você aprende:
Nem tudo é perfeito no mundo de blocos
Programação exige adaptação
Aproximação matemática

## 🟣 Fase 4 — Círculo e Disco
Círculo (contorno)
circulo 10

O Agent usa matemática:
x² + z² ≈ raio²

Ele verifica cada ponto ao redor e decide se coloca bloco.

O que você aprende:
Fórmula matemática aplicada
Como computadores “testam condições”
Como criar formas arredondadas no grid

Disco (preenchido)
disco 7

Em vez de só a borda, ele preenche tudo dentro do raio.

O que você aprende:
Diferença entre contorno e área
Condições matemáticas no código

## 🔴 Fase 5 — Montanha-russa

Agora você constrói algo funcional.

Estação
estacao 8 10

Cria:
Piso
Trilho central
Você aprende:
Construção em camadas
Separação entre estrutura e função

Trilho reto
trilhoReto 12

O Agent anda em linha reta colocando trilhos.

Você aprende:
Sequência
Repetição linear

Curvas
curvaDireita 6
curvaEsquerda 6

O Agent:

Anda
Vira
Anda
Vira

Você aprende:
Controle de direção
Mudança de orientação

Subida
subida 8

O Agent:
Sobe
Avança
Coloca suporte

Você aprende:

Movimento no eixo Y (altura)
Construção tridimensional

Descida
descida 8

O Agent:
Avança
Desce

Você aprende:
Controle vertical
Continuidade estrutural

Montanha automática
montanha 1

## Executa um roteiro completo:

Reta
Curva
Subida
Reta alta
Descida
Retorno