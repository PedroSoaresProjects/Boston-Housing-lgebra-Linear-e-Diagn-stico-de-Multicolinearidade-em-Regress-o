# Análise do Boston Housing Dataset com Álgebra Linear

## Visão Geral

Este projeto apresenta uma análise exploratória do Boston Housing Dataset utilizando Python, com foco na aplicação de conceitos de álgebra linear em problemas de regressão e diagnóstico de multicolinearidade.

A análise foi desenvolvida como parte de um estudo mais aprofundado sobre o papel da estrutura matricial em modelos de regressão linear e sobre como ferramentas da álgebra linear podem auxiliar na compreensão da estabilidade numérica desses modelos.

---

## Objetivos

O objetivo principal deste projeto é investigar como conceitos de álgebra linear podem ser aplicados na análise de dados e em modelos de regressão.

Entre os pontos explorados estão:

- Construção da matriz de regressão
- Análise do posto da matriz
- Cálculo do número de condição para diagnóstico de multicolinearidade
- Avaliação dos autovalores da matriz \(X^TX\)
- Cálculo do coeficiente de correlação de Pearson
- Visualização de relações entre variáveis por meio de gráficos de dispersão

---

## Conjunto de Dados

O estudo utiliza o Boston Housing Dataset, que contém 506 observações e 14 variáveis relacionadas a características estruturais e socioeconômicas de áreas urbanas.

Variável resposta:

- **MEDV** – valor mediano das casas ocupadas por proprietários.

Algumas variáveis analisadas:

- **RM** – número médio de quartos por residência  
- **LSTAT** – porcentagem da população de baixo status socioeconômico  
- **CRIM** – taxa de criminalidade per capita por região

---

## Análise Exploratória

O projeto explora relações entre algumas variáveis relevantes do conjunto de dados, incluindo:

- RM e MEDV  
  Áreas com maior número médio de quartos tendem a apresentar preços de imóveis mais elevados.

- LSTAT e MEDV  
  Regiões com maior proporção de população de baixo status socioeconômico tendem a apresentar preços médios mais baixos.

- RM e LSTAT  
  A relação negativa sugere que áreas com casas maiores tendem a apresentar menor proporção de população de baixo status socioeconômico.

Essas relações são visualizadas por meio de gráficos de dispersão e ajustes lineares simples.

---

## Diagnóstico com Álgebra Linear

Para compreender melhor a estrutura do problema de regressão, foram analisados:

- Posto da matriz de regressão \(X\)
- Posto da matriz \(X^TX\)
- Número de condição de \(X^TX\)
- Autovalores da matriz \(X^TX\)

Essas análises ajudam a avaliar possíveis problemas de multicolinearidade e a estabilidade numérica das estimativas do modelo.

---

## Ferramentas Utilizadas

- Python  
- Pandas  
- NumPy  
- Matplotlib  



