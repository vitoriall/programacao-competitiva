# Programação Competitiva - Lista de Prática

Este repositório contém questões de prática de programação competitiva, nível iniciante e intermediário, para reforçar conceitos como operações matemáticas, condicionais, laços e manipulação de dados.

---

## 📚 Lista 1 - Nível 1 e 2

---

### ✅ Questão 1 — Média Ponderada Invertida

**Descrição:**  
Leia três valores correspondentes às notas de um aluno. Calcule a média ponderada invertida, onde os pesos são aplicados de forma contrária:  
- O primeiro valor tem peso **5**.  
- O segundo tem peso **3**.  
- O terceiro tem peso **2**.  

**Fórmula:**  
media = (nota1 * 5 + nota2 * 3 + nota3 * 2) / 10

**Entrada:**  
Três números reais.

**Saída:**  
Imprimir a média ponderada no formato:
MEDIA = X.X
Com **1 casa decimal**.

**Exemplo:**  
Entrada:
8.0 6.0 7.0

Saída:
MEDIA = 7.1

---

### ✅ Questão 2 — Distância 3D

**Descrição:**  
Calcule a distância entre dois pontos no espaço tridimensional.

**Fórmula:**  
distancia = sqrt((x2 - x1)^2 + (y2 - y1)^2 + (z2 - z1)^2)

**Entrada:**  
Seis números reais representando as coordenadas dos dois pontos:  
`x1 y1 z1 x2 y2 z2`

**Saída:**  
A distância entre os pontos, com **4 casas decimais**.

**Exemplo:**  
Entrada:
1.0 2.0 3.0 4.0 5.0 6.0

Saída:
5.1962

Outro exemplo:  
Entrada:
0.0 0.0 0.0 1.0 1.0 1.0

Saída:
1.7321

---

### ✅ Questão 3 — Converter Minutos

**Descrição:**  
Dado um valor inteiro em minutos, converta para **horas e minutos**.

**Regra:**  
- 1 hora = 60 minutos

**Entrada:**  
Um número inteiro representando minutos.

**Saída:**  
Formato:
X hora(s)
Y minuto(s)

**Exemplo:**  
Entrada:
130

Saída:
2 hora(s)
10 minuto(s)

Outro exemplo:  
Entrada:
59

Saída:
0 hora(s)
59 minuto(s)

---

### ✅ Questão 4 — Verificar Intervalo Personalizado

**Descrição:**  
Dado um intervalo `[A, B]` e uma sequência de N números inteiros, determine quantos estão **dentro** (inclusive nas bordas) e quantos estão **fora** desse intervalo.

**Entrada:**  
- Dois inteiros `A B` representando os limites do intervalo.  
- Um inteiro `N` representando a quantidade de números.  
- N inteiros.

**Saída:**  
X in
Y out

**Exemplo:**  
Entrada:
10 20
5
15 8 25 18 10

Saída:
3 in
2 out

Outro exemplo:  
Entrada:
5 15
4
3 7 16 10

Saída:
2 in
2 out

---

### ✅ Questão 5 — Quantos Acertaram?

**Descrição:**  
O jogo consiste em adivinhar um número secreto. Dado o número correto e as respostas de 5 competidores, determine quantos acertaram.

**Entrada:**  
- Um inteiro `T` representando o número correto.  
- Cinco inteiros representando as tentativas dos jogadores.

**Saída:**  
X acertaram

**Exemplo:**  

Entrada:
42
12 42 7 42 90

Saída:
2 acertaram

Outro exemplo:  
Entrada:
15
1 2 3 4 5

Saída:
0 acertaram

---

## 🧠 Observações
- As saídas devem ser exatamente no formato apresentado, com quebras de linha quando indicado.
- As entradas sempre são válidas e seguem o padrão dos exemplos.

---

## 🚀 Organização dos Arquivos
/lista-1
├── media-invertida.cpp
├── distancia-3d.cpp
├── converter-minutos.cpp
├── intervalo-personalizado.cpp
└── quantos-acertaram.cpp

/testes
├── media-invertida.txt
├── distancia-3d.txt
├── converter-minutos.txt
├── intervalo-personalizado.txt
└── quantos-acertaram.txt

---

## 👾 Objetivo
Praticar lógica de programação, estrutura de dados simples e consolidar fundamentos para competições como:  
- **Maratona SBC**  
- **GEPC UFC**  
- **Beecrowd**  
- **Outras plataformas de juízes online**

---

🔥 Bora codar e subir pro GitHub! Bora ficar BRABO na programação competitiva! 💪🚀
