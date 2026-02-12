# 📊 Análise de Vendas de E-commerce — Dataset Olist

Projeto de análise de dados focado em um cenário real de negócio utilizando o **Brazilian E-Commerce Public Dataset by Olist**.  
O objetivo é explorar dados de vendas de um e-commerce brasileiro para extrair insights relevantes sobre comportamento de compra, tendências e desempenho de produtos.

---

## 🎯 Objetivo

Analisar dados de vendas para responder perguntas de negócio como:

- Quantidade de pedidos por mês/ano
- Categorias de produtos mais vendidas
- Estados (UF) com maior número de clientes
- Valor médio de compra por cliente
- Tendências temporais de vendas

---

## 📂 Dataset

Brazilian E-Commerce Public Dataset by Olist

O dataset contém múltiplas tabelas relacionadas, como:

- orders
- customers
- order_items
- products
- payments

Esse formato permite praticar uma das habilidades mais importantes em análise de dados:

👉 Integração de dados usando `pd.merge()`.

---

## 🧩 Etapas do Projeto

### ✅ 1. Carregamento dos Dados
- Importação de múltiplos arquivos CSV em DataFrames utilizando Pandas.

### ✅ 2. Limpeza e Preparação
- Verificação de dados faltantes:
```python
df.isnull().sum()
