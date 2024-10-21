
### 📦 Análise ABC-XYZ com Machine Learning

Bem-vindo ao projeto **Análise ABC-XYZ com Machine Learning**! Este repositório contém um notebook Jupyter que utiliza técnicas de machine learning para realizar análises ABC e XYZ em um conjunto de dados de vendas. Abaixo, você encontrará um guia abrangente sobre o que este notebook faz, como usá-lo e como estruturar seus dados de entrada.

## 📚 Índice

- [Visão Geral](#visão-geral)
- [Descrição das Análises](#descrição-das-análises)
- [Estrutura dos Dados de Entrada](#estrutura-dos-dados-de-entrada)
- [Dependências](#dependências)
- [Uso](#uso)
- [Saída](#saída)

## 📋 Visão Geral

Este notebook utiliza técnicas de machine learning, especificamente o algoritmo K-means, para realizar análises ABC e XYZ. A análise ABC classifica os produtos com base em sua importância relativa, enquanto a análise XYZ classifica os produtos com base na variabilidade da demanda.

## 🔍 Descrição das Análises

### Análise ABC

A análise ABC classifica os produtos em três categorias com base na importância relativa:
- **Classe A:** Produtos de alta importância
- **Classe B:** Produtos de importância moderada
- **Classe C:** Produtos de baixa importância

Utiliza-se o K-means para considerar múltiplas variáveis simultaneamente (volume de vendas, valor monetário e frequência de venda), proporcionando uma visão mais holística.

### Análise XYZ

A análise XYZ classifica os produtos com base na variabilidade da demanda:
- **Classe X:** Demanda estável
- **Classe Y:** Demanda moderadamente variável
- **Classe Z:** Demanda altamente variável

Utiliza-se a técnica de análise de séries temporais e aplicação de modelos de clustering para automatizar essa classificação.

### Combinação ABC-XYZ

A combinação das classificações ABC e XYZ resulta em nove combinações possíveis, cada uma com características distintas em termos de valor e variabilidade da demanda. Estratégias sugeridas são detalhadas para cada combinação.

## 📂 Estrutura dos Dados de Entrada

Os dados de entrada devem estar em um arquivo Excel contendo as seguintes colunas:
- **volume_vendas:** Volume de vendas dos produtos.
- **valor_monetario:** Valor monetário das vendas dos produtos.
- **frequencia_vendas:** Frequência de vendas dos produtos.

## 🛠 Dependências

Certifique-se de ter as seguintes dependências instaladas:

- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

Instale-as usando pip:

```bash
pip install requirements.txt
```

## 🚀 Uso

1. Clone este repositório:

Apenas rode cada uma das celulas do notebook.
   ```

## 📈 Saída

Após executar o notebook, você obterá:

- **Classificação ABC:** Produtos classificados em A, B ou C.
- **Classificação XYZ:** Produtos classificados em X, Y ou Z.
- **Combinação ABC-XYZ:** Uma tabela combinando as classificações ABC e XYZ para cada produto.

### Exemplo de Saída

```plaintext
Produto | ABC_Class | XYZ_Class | Combinação
---------------------------------------------
Prod1   | A         | X         | AX
Prod2   | B         | Y         | BY
...
```
---

Feito com 🧠 por [Vitor Tatekawa](https://github.com/vtatekawa)
