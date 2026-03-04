# 📊 Análise de Churn de clientes da empresa TelecomX

![Badge Concluído](http://img.shields.io/static/v1?label=STATUS&message=CONCLUÍDO&color=GREEN&style=for-the-badge)
![Badge Python](http://img.shields.io/static/v1?label=Tech&message=PYTHON&color=blue&style=for-the-badge)

## 💼 Descrição do Projeto

O presente relatório documenta as etapas e descobertas do projeto de análise de dados focado no Churn de Clientes da empresa de telecomunicações Telecom X. O Churn (taxa de cancelamento) é uma das métricas mais críticas para empresas de serviços recorrentes, pois o custo de aquisição de um novo cliente é significativamente maior do que o custo de retenção.

## 🎯 Objetivo
Analisar a base de dados histórica da Telecom X para identificar os principais fatores e padrões que levam à evasão de clientes, fornecendo uma base sólida de Data Science para a futura criação de modelos preditivos e campanhas de retenção.

---

## 🛠️ Tecnologias Utilizadas

* **Python:** Linguagem base para análise.
* **Pandas:** Carregamento de dados (ETL), limpeza e manipulação de DataFrames.
* **Matplotlib e Seaborn:** Visualização de dados para criação de gráficos comparativos.
* **Jupyter Notebook:** Ambiente de desenvolvimento e documentação.

---

## 🔍 Principais Insights da Análise

Durante a exploração dos dados, levantei pontos cruciais que direcionaram a tomada de decisão:

### 💰 1. Performance Financeira (Faturamento)
A métrica principal de decisão. Ao consolidar as vendas, identificou-se um *gap* de performance:
* **Loja 1 (Líder):** R$ 1.534.509,12
* **Loja 4 (Menor Receita):** R$ 1.384.497,58

> **Insight:** A Loja 4 arrecada cerca de **R$ 150.000,00 a menos** que a líder, indicando ineficiência comercial.

### ⭐ 2. Qualidade Percebida (Avaliações)
Havia a hipótese de que a loja com pior venda teria o pior atendimento. **Os dados refutaram isso.**
* Média geral das lojas: ~4.0
* A análise mostrou uma **homogeneidade** entre as filiais.

> **Conclusão:** O problema da Loja 4 **não é** a qualidade do serviço ou do produto, visto que há um empate técnico na satisfação do cliente.

### 🚚 3. Eficiência Logística (Frete)
Os custos de frete variaram pouco (R$ 31,00 - R$ 35,00).
* A Loja 4 possui um frete competitivo (faixa inferior), mas isso não se traduziu em vendas.
* Isso isola o problema: ter frete barato não está salvando a operação da Loja 4.

---

## 💡 Conclusão e Recomendação

Com base na análise de dados, a recomendação oficial para o *stakeholder* é a **venda da Loja 4**.

### ⚖️ Justificativa da Decisão:
1.  **Menor Retorno Financeiro:** É a unidade com o menor volume de receita (R$ 1.38 Mi), consistentemente atrás das concorrentes internas.
2.  **Problema Estrutural:** O fato de ter boas avaliações e frete competitivo, mas ainda assim vender pouco, sugere problemas estruturais de localização ou demanda de mercado que dificilmente serão resolvidos a curto prazo.
3.  **Custo de Oportunidade:** Vender a unidade menos eficiente libera capital para investimentos com maior potencial de retorno.

---

## 📈 Visualizações

<img width="1323" height="590" alt="image" src="https://github.com/user-attachments/assets/3fffec27-322c-4b02-b297-fcab6f62756e" />

*Distribuição absoluta e percentual da evasão dos clientes.*

<br>

<img width="1572" height="1190" alt="image" src="https://github.com/user-attachments/assets/57d6ff89-fa52-4ffc-a127-947b156ec3ee" />

*Distribuição da evasão por variáveis categóricas.*

<br>

<img width="1790" height="490" alt="image" src="https://github.com/user-attachments/assets/f73870f4-f97a-4a0b-bf00-7e71159d3529" />

*Distribuição da evasão por variáveis numéricas.*

---

## 🙋‍♂️ Autor

Feito por Julio Freitas.
Entre em contato!

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/juliofrs) 
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:juliofreitaspro@gmail.com)
