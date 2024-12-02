# Cybersecurity Attacks: Análise e Predição de Severidade

[![Overleaf](https://img.shields.io/badge/Overleaf-View%20Paper-green)](https://www.overleaf.com/read/yrpsnvhqxfny#b43068)
[![Python](https://img.shields.io/badge/Python-3.x-blue)](https://www.python.org/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange)](https://www.tensorflow.org/)

Este projeto utiliza aprendizado de máquina para analisar dados de ataques cibernéticos e predizer o nível de severidade. O trabalho abrange desde o pré-processamento dos dados até a aplicação de redes neurais, destacando diagnósticos, desafios e melhorias.

---

## 📑 **Sumário**
- [Visão Geral](#visão-geral)
- [Resultados](#resultados)
- [Requisitos](#requisitos)
- [Como Usar](#como-usar)
- [Referências](#referências)

---

## 🧐 **Visão Geral**
O objetivo principal é predizer a variável alvo `Severity Level` com base em um conjunto de dados contendo informações de ataques cibernéticos. A pesquisa aborda:
1. Pré-processamento de dados, tratamento de valores ausentes e detecção de outliers.
2. Análise exploratória com visualizações, incluindo heatmaps para correlação entre ataques e datas.
3. Construção e comparação de diferentes topologias de redes neurais para melhorar a performance preditiva.

O paper completo, com detalhes sobre métodos e resultados, está disponível [aqui](https://www.overleaf.com/read/yrpsnvhqxfny#b43068).

---

## 🎯 **Resultados**
- **Análise de Dados**:
  - Tratamento eficaz de valores faltantes e outliers.
  - Balanceamento dos dados utilizando SMOTE para melhorar a representação das classes.
  - Visualização da correlação entre dias da semana e número de ataques por ano.

- **Modelagem com Redes Neurais**:
  - Foram testadas três topologias diferentes, ajustando a arquitetura, hiperparâmetros e taxa de aprendizado.
  - Apesar dos desafios iniciais com baixa acurácia (~33\%), melhorias propostas no modelo e no balanceamento dos dados resultaram em desempenho aprimorado.

- **Conclusão**:
  - Diagnósticos de baixa performance, possíveis causas e estratégias de solução foram identificadas e documentadas. 

---

## 💻 **Requisitos**
Antes de começar, instale as seguintes dependências:

- Python 3.8 ou superior
- Bibliotecas:
  - `numpy`
  - `pandas`
  - `seaborn`
  - `matplotlib`
  - `scikit-learn`
  - `tensorflow`
  - `imblearn`

Instale tudo com:
```bash
pip install -r requirements.txt

⚙️Como Usar
git clone https://github.com/seu-usuario/cybersecurity-attacks.git
cd cybersecurity-attacks
E certifiquese que o arquivo esteja com o nome cybersecurity_attacks.csv no diretorio raiz.

📚 Referências
Referências Acadêmicas:
Paper Oficial: Cybersecurity Attacks - Predição de Severidade
Artigo detalhado explicando os métodos utilizados no projeto.
Documentação de Bibliotecas:
TensorFlow: Documentação Oficial
Guia completo para construir e treinar modelos de aprendizado de máquina.

Imbalanced-learn: SMOTE e Técnicas de Balanceamento
Biblioteca para lidar com datasets desbalanceados.
