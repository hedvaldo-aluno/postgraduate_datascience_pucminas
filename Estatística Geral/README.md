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

