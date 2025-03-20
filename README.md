<h1 align="center">Análise de Qualidade do Vinho</h1>

<p align="center"><i>Repositório dedicado à análise de dados e correlação entre variáveis relacionadas à qualidade do vinho.</i></p>

<p align="center" display="inline-block">
  <img src="https://img.shields.io/badge/Status-Ativo-brightgreen" alt="Status"/>
  <img src="https://img.shields.io/badge/Python-3.8%2B-blue?logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/Seaborn-v0.11.2-yellowgreen?logo=seaborn&logoColor=white" alt="Seaborn"/>
  <img src="https://img.shields.io/badge/Pandas-v1.5.0-green?logo=pandas&logoColor=white" alt="Pandas"/>
  <img src="https://img.shields.io/badge/Matplotlib-v3.4.3-red?logo=matplotlib&logoColor=white" alt="Matplotlib"/>
</p>

## Sobre este projeto

Este repositório contém um código de análise de dados para investigar a qualidade do vinho com base em várias características, como acidez, álcool, sulfatos e outros compostos químicos. Utilizando o conjunto de dados [**Red Wine Quality**](https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009) disponível no **Kaggle**, a análise inclui a visualização das distribuições de variáveis, correlações entre elas, além de insights sobre como variáveis como álcool, sulfatos e acidez influenciam a qualidade do vinho.

### Objetivo
O objetivo deste projeto é explorar o conjunto de dados de vinhos, entender a relação entre diferentes características e a qualidade do vinho, e visualizar essas relações por meio de gráficos interativos.

---

## Visualizações

### 1. **Matriz de Correlação**
A matriz de correlação mostra como as variáveis estão relacionadas entre si. A qualidade do vinho, por exemplo, tem forte correlação com o álcool, sulfatos e acidez.

![dadasd](https://github.com/user-attachments/assets/136ec631-52a2-4e3e-9791-84b6569cae95)

**Explicação**: A matriz de correlação exibe os coeficientes de correlação entre as variáveis. Os valores próximos de 1 ou -1 indicam uma forte correlação, enquanto valores próximos de 0 indicam fraca ou nenhuma correlação.

### 2. **Relação entre Álcool e Sulfatos**
Este gráfico de dispersão mostra a relação entre o teor alcoólico e os sulfatos no vinho, colorido por qualidade.

![asdasdawlasd](https://github.com/user-attachments/assets/869a1b12-a005-46b4-9f35-5d09eb43fd16)


**Explicação**: O gráfico mostra como o teor alcoólico e a concentração de sulfatos estão relacionados. A qualidade do vinho é influenciada por esses dois fatores.

### 3. **Distribuição do Teor Alcoólico**

![asdalidhwasd](https://github.com/user-attachments/assets/5215c012-01f8-4b9e-b8e8-bd406ed39725)


**Explicação**: A distribuição do teor alcoólico nos vinhos mostra que a maioria dos vinhos tem teor alcoólico moderado, Isso nos dá uma visão geral sobre a variação do teor alcoólico nos vinhos do conjunto de dados.

---

## Como Rodar o Projeto

1. Clone o repositório:
```bash
  git clone https://github.com/cf-neto/Analise-Qualidade-Vinho.git
