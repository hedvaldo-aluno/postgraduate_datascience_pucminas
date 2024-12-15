> **“Estatística: a ciência que diz que se eu comi um frango e tu não comeste nenhum, teremos comido, em média, meio frango cada um.”**  
> *— Dino "Pitigrilli" Segrè*

# Estatística Geral
A estatística é uma área da matemática que se dedica à coleta, organização, análise, interpretação e apresentação de dados. Seu objetivo principal é transformar dados brutos em informações úteis que auxiliem na tomada de decisões.

## Dados Qualitativos

Os dados qualitativos (ou categóricos) são aqueles que descrevem atributos ou características e não podem ser quantificados numericamente. Exemplos incluem sexo, cor dos olhos, estado civil, etc. Esses dados são geralmente divididos em categorias ou grupos e podem ser analisados por meio de contagem ou proporções.

---

## Dados Quantitativos

Os dados quantitativos são aqueles que podem ser medidos e expressos numericamente. Exemplos incluem idade, altura, peso, tempo de conclusão de tarefas, entre outros. Esses dados podem ser analisados por meio de médias, medianas, desvios padrões, entre outras medidas estatísticas.

---

## Medidas de Tendência Central

As medidas de tendência central são ferramentas estatísticas utilizadas para resumir um conjunto de dados, indicando um valor representativo ou central. Elas ajudam a identificar padrões e tendências nos dados. As principais medidas de tendência central são:

- **Média:** É a soma de todos os valores dividida pelo número total de observações. É sensível a valores extremos.  
  **Fórmula:**  
  $\text{Média} = \frac{\text{soma dos valores}}{\text{número de observações}}$

- **Mediana:** É o valor central de um conjunto de dados ordenado. Quando o número de observações é par, a mediana é a média dos dois valores centrais. A mediana não é influenciada por valores extremos.

- **Moda:** É o valor que mais se repete em um conjunto de dados. Um conjunto pode ser:
  - **Sem moda:** Nenhum valor se repete.
  - **Unimodal:** Apenas um valor se repete com mais frequência.
  - **Multimodal:** Dois ou mais valores ocorrem com a mesma frequência máxima.

**Exemplo:**
Para o conjunto de dados: $\{2, 3, 3, 5, 7\}$:
- **Média:** $\frac{2 + 3 + 3 + 5 + 7}{5} = 4$
- **Mediana:** $3$
- **Moda:** $3$

## Medidas de Dispersão

As medidas de dispersão são ferramentas estatísticas utilizadas para descrever a variabilidade ou a dispersão dos dados em um conjunto. Elas complementam as medidas de tendência central, fornecendo uma visão sobre o quão espalhados os valores estão em relação ao centro. As principais medidas de dispersão são:

### **1. Amplitude**
A amplitude é a diferença entre o maior e o menor valor do conjunto de dados.  
**Fórmula:**  
$\text{Amplitude} = \text{Valor Máximo} - \text{Valor Mínimo}$  
**Limitação:** Não considera como os dados estão distribuídos, apenas os valores extremos.

---

### **2. Variância**
A variância mede a média dos quadrados das diferenças entre cada valor e a média do conjunto de dados. É expressa em unidades ao quadrado, tornando-se difícil de interpretar diretamente.  
**Fórmula para amostra:**  
$\text{Variância (s²)} = \frac{\sum (x_i - \bar{x})^2}{n - 1}$  
**Fórmula para população:**  
$\text{Variância (σ²)} = \frac{\sum (x_i - \mu)^2}{N}$

---

### **3. Desvio Padrão**
O desvio padrão é a raiz quadrada da variância e é expresso nas mesmas unidades dos dados originais, facilitando a interpretação.  
**Fórmula:**  
$\text{Desvio Padrão (s)} = \sqrt{\text{Variância}}$  
O desvio padrão indica o quão dispersos estão os dados em relação à média: quanto maior o valor, maior a variabilidade.

---

### **4. Coeficiente de Variação (CV)**
O coeficiente de variação é uma medida relativa de dispersão, expressa em porcentagem, que indica a relação entre o desvio padrão e a média. É útil para comparar a variabilidade entre conjuntos de dados com escalas diferentes.  
**Fórmula:**  
$\text{CV} = \frac{\text{Desvio Padrão}}{\text{Média}} \times 100$

---

### **5. Amplitude Interquartil (IQR)**
A amplitude interquartil é a diferença entre o terceiro quartil (Q3) e o primeiro quartil (Q1), representando a dispersão dos valores centrais de um conjunto de dados.  
**Fórmula:**  
$\text{IQR} = Q3 - Q1$  
É menos sensível a outliers do que a amplitude total.

---

## Medidas de Posição Relativa

As medidas de posição relativa são ferramentas estatísticas utilizadas para identificar a localização de um dado dentro de um conjunto, em relação aos outros valores. Elas ajudam a entender a posição de um valor específico no contexto dos dados analisados. As principais medidas de posição relativa são:

---

### **1. Quartis**
Os quartis dividem um conjunto de dados ordenado em quatro partes iguais.  
- **Q1 (primeiro quartil):** 25% dos dados estão abaixo desse valor.  
- **Q2 (segundo quartil ou mediana):** 50% dos dados estão abaixo desse valor.  
- **Q3 (terceiro quartil):** 75% dos dados estão abaixo desse valor.  

**Fórmula:**  
$\text{Posição do Quartil} = \frac{k(n+1)}{4}$  
Onde \(k\) é o número do quartil (1, 2 ou 3) e \(n\) é o número de observações.

---

### **2. Percentis**
Os percentis dividem os dados em 100 partes iguais, indicando a posição de um dado em relação ao conjunto.  
**Exemplo:** O 90º percentil indica que 90% dos dados estão abaixo desse valor.

**Fórmula:**

$\text{Posição do Percentil} = \left( \frac{K}{100} \right) \times n$  

Onde \(K\) é o percentil desejado e \(n\) é o número de observações.

---
**Exemplo de Cálculo de Percentil**
Um pesquisador está interessado em avaliar o tempo (em segundos) que aproximadamente 75% dos consumidores demoram entre o início e a finalização de uma compra em um determinado site na Internet. Para isso, observou 12 consumidores escolhidos aleatoriamente no sistema. Os dados encontram-se abaixo:

**Dados:**  
71, 73, 73, 74, 74, 75, 76, 77, 77, 79, 81, 83  

**Cálculo do Percentil 75:**  
1. Fórmula para a posição do percentil:  
   $\text{L} = \left( \frac{75}{100} \right) \times 12$  
   $\text{L} = 9$  

2. Como o resultado é um número inteiro, calculamos a média entre o valor da 9ª posição e o valor da 10ª posição:  
   $\text{L} = \frac{77 + 79}{2} = 78$  

**Conclusão:**  
Aproximadamente 75% dos consumidores demoram até **78 segundos** entre o início e a finalização da compra.

---

### **3. Decis**
Os decis dividem os dados em 10 partes iguais.  
- O 1º decil indica que 10% dos dados estão abaixo desse valor.  
- O 5º decil corresponde à mediana (50%).

**Fórmula:**  
$\text{Posição do Decil} = \frac{d(n+1)}{10}$  
Onde \(d\) é o número do decil (1 a 9).

---

### **4. Escore-Z**
O escore-z mede a posição de um valor em termos de desvios padrão da média. Ele indica o quão longe um dado está da média do conjunto.  
**Fórmula:**  
$Z = \frac{x - \bar{x}}{s}$  
Onde:  
- \(x\) é o valor observado.  
- \($\bar{x}$) é a média.  
- \(s\) é o desvio padrão.  

Valores de escore-z:  
- \(Z > 0\): O valor está acima da média.  
- \(Z < 0\): O valor está abaixo da média.  
- \(Z = 0\): O valor é igual à média.
---

## Probabilidade
A probabilidade é uma medida numérica da possibilidade de um evento ocorrer. Valores probabilísticos são sempre atribuídos em uma escala de 0 a 1. Uma probabilidade próxima de 0 indica que é pouco provável que um evento ocorra; uma probabilidade próxima de 1 revela que a ocorrência de um evento é quase certa.

### **Espaço amostral**
Chama-se espaço amostral o conjunto de todos os possíveis resultados de um experimento aleatório ou, em outras palavras, é o conjunto universo relativo aos resultados de um experimento.

**Evento:** É um subconjunto de elementos do espaço amostral.

### **Axiomas de probabilidade**
Dado um espaço amostral, Ω, suponha que estamos estudando um evento A. A probabilidade do evento A ocorrer é denotada por P(A). A função P(A) só será uma probabilidade se ela satisfaz três condições básicas:
* 0 ≤ P(A) ≤ 1
* P(Ω) = 1
* P(A1 ∪ A2 ∪ A3 ∪...) = P(A1)+P(A2)+P(A3)+..., se os eventos A1, A2,... forem
disjuntos (isto é, mutuamente exclusivos).

## Árvore de Probabilidade

A **árvore de probabilidade** é uma ferramenta visual usada em estatística e probabilidade para organizar e calcular probabilidades de eventos compostos. É especialmente útil para entender problemas envolvendo múltiplos eventos, possibilitando uma visão clara de todas as possíveis combinações e seus resultados.

### Estrutura de uma Árvore de Probabilidade

1. **Ramos (ou galhos)**: Representam os diferentes eventos ou escolhas possíveis.
2. **Nós**: Pontos onde os ramos se bifurcam, indicando o início de novos eventos ou decisões.
3. **Probabilidades**: Atribuídas a cada ramo, indicando a chance de cada evento ocorrer.
4. **Caminhos completos**: Representam sequências de eventos, e suas probabilidades podem ser calculadas multiplicando as probabilidades ao longo de cada caminho.

### Como Construir uma Árvore de Probabilidade

1. **Identifique os eventos**: Liste todos os eventos possíveis que podem ocorrer em cada estágio.
2. **Desenhe os ramos**: Para cada evento, desenhe um ramo a partir de um nó inicial.
3. **Adicione probabilidades**: Atribua a probabilidade de cada evento a seu respectivo ramo.
4. **Calcule probabilidades compostas**: Multiplique as probabilidades ao longo dos ramos para encontrar a probabilidade total de cada resultado.


Cada caminho da árvore representa um resultado possível, e a probabilidade de cada caminho é dada por:

- Cara → Cara: $P(\text{Cara, Cara})=\frac{1}{2}\times\frac{1}{2}=\frac{1}{4}$
- Cara → Coroa: $P(\text{Cara, Coroa})=\frac{1}{2}\times\frac{1}{2}=\frac{1}{4}$
- Coroa → Cara: $P(\text{Coroa, Cara})=\frac{1}{2}\times\frac{1}{2}=\frac{1}{4}$
- Coroa → Coroa: $P(\text{Coroa, Coroa})=\frac{1}{2}\times\frac{1}{2}=\frac{1}{4}$

## Probabilidade Condicional
A probabilidade condicional mede a probabilidade de um evento ocorrer dado que outro evento já ocorreu. É uma ferramenta essencial na teoria da probabilidade, sendo usada para modelar situações onde eventos estão relacionados.

### Definição
A probabilidade condicional de um evento $A$ dado que o evento $B$ ocorreu é representada por $P(A \mid B)$ e é calculada como:

$$
P(A \mid B) = \frac{P(A \cap B)}{P(B)}
$$

**Onde:**
- $P(A \mid B)$: Probabilidade de $A$ dado que $B$ ocorreu.
- $P(A \cap B)$: Probabilidade de $A$ e $B$ ocorrerem juntos.
- $P(B)$: Probabilidade de $B$ ocorrer. Deve ser maior que zero ($P(B) > 0$).

### Exemplo Prático

Considere o seguinte cenário: um baralho de 52 cartas. Qual é a probabilidade de uma carta ser um ás dado que já sabemos que ela é uma carta de espadas?

**Passo a passo:**

1. Identifique as probabilidades relevantes:
   - Existem 13 cartas de espadas, ou seja, $P(B) = \frac{13}{52}$.
   - Apenas 1 dessas cartas de espadas é um ás, ou seja, $P(A \cap B) = \frac{1}{52}$.

2. Use a fórmula da probabilidade condicional:
   $P(A \mid B) = \frac{P(A \cap B)}{P(B)}$

3. Substitua os valores:
   $P(A \mid B) = \frac{\frac{1}{52}}{\frac{13}{52}} = \frac{1}{13}$

Portanto, a probabilidade de a carta ser um ás dado que ela é uma carta de espadas é $P(A \mid B) = \frac{1}{13}$.

### Propriedades

1. **Dependência entre eventos**:
   - Se $P(A \mid B) \neq P(A)$, os eventos $A$ e $B$ são dependentes.
   - Se $P(A \mid B) = P(A)$, os eventos $A$ e $B$ são independentes.

2. **Multiplicação de probabilidades**:
   A probabilidade de $A$ e $B$ ocorrerem pode ser escrita em termos da probabilidade condicional:
   $P(A \cap B) = P(A \mid B) \cdot P(B)$

3. **Teorema da probabilidade total**:
   Quando há vários eventos que particionam o espaço amostral, a probabilidade de um evento pode ser calculada somando as probabilidades condicionais ponderadas:
   $P(A) = \sum_{i} P(A \mid B_i) \cdot P(B_i)$

## Teorema de Bayes
O teorema de Bayes demonstra que aquele que pensa no problema também influencia a probabilidade de um evento ocorrer com base no que ele sabe a priori sobre este evento.

O Teorema de Bayes é expresso como:

$P(A \mid B) = \frac{P(B \mid A) \cdot P(A)}{P(B)}$

**Onde:**
- $P(A \mid B)$: Probabilidade de $A$ dado que $B$ ocorreu (probabilidade condicional).
- $P(B \mid A)$: Probabilidade de $B$ dado que $A$ ocorreu.
- $P(A)$: Probabilidade a priori de $A$ (antes de considerar $B$).
- $P(B)$: Probabilidade de $B$ (normalizador, garantindo que o resultado seja uma probabilidade válida).

### Exemplo Prático

Imagine um teste para uma doença que tem os seguintes dados:

- A doença afeta 1% da população: $P(\text{Doença}) = 0.01$.
- O teste tem uma taxa de acerto de 95% para pessoas com a doença: $P(\text{Positivo} \mid \text{Doença}) = 0.95$.
- O teste tem uma taxa de 5% de falsos positivos: $P(\text{Positivo} \mid \text{Sem Doença}) = 0.05$.

Se uma pessoa testa positivo, qual é a probabilidade de ela realmente ter a doença?

**Passo a passo:**
1. Probabilidade de não ter a doença:
   $P(\text{Sem Doença}) = 1 - P(\text{Doença}) = 0.99$

2. Probabilidade de o teste dar positivo:
   $P(\text{Positivo}) = P(\text{Positivo} \mid \text{Doença}) \cdot P(\text{Doença}) + P(\text{Positivo} \mid \text{Sem Doença}) \cdot P(\text{Sem Doença})$

   Substituindo:
   $P(\text{Positivo}) = (0.95 \cdot 0.01) + (0.05 \cdot 0.99) = 0.0095 + 0.0495 = 0.059$

3. Aplicando o Teorema de Bayes:
   $P(\text{Doença} \mid \text{Positivo}) = \frac{P(\text{Positivo} \mid \text{Doença}) \cdot P(\text{Doença})}{P(\text{Positivo})}$

   Substituindo:
   $P(\text{Doença} \mid \text{Positivo}) = \frac{0.95 \cdot 0.01}{0.059} \approx 0.161 \$

Apesar do teste positivo, a probabilidade de ter a doença é de apenas **16,1%**, devido à baixa prevalência da doença.
