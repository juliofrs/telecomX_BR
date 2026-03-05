# ☎️ Telecom X: Análise de Evasão de Clientes (Churn)

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google_Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white)

## 💼 Descrição do Projeto

Este projeto de Ciência de Dados foca em resolver um dos problemas mais clássicos e custosos para empresas de serviços recorrentes: o **Churn (Evasão de Clientes)**. O Churn é uma das métricas mais críticas para empresas de serviços recorrentes, pois o custo de aquisição de um novo cliente é significativamente maior do que o custo de retenção. O presente relatório documenta as etapas e descobertas do projeto de análise de dados focado no Churn de Clientes da empresa de telecomunicações Telecom X. 

## 🎯 Objetivo

Atuando como analista de dados para a empresa fictícia **Telecom X**, o objetivo foi investigar uma base de dados com mais de 7.000 registros para descobrir os fatores que levam à perda de clientes. A partir da coleta, tratamento e análise (EDA) de variáveis demográficas, financeiras e de serviços, extraímos insights valiosos para embasar estratégias de retenção e futuras aplicações de Machine Learning.

---

## 🛠️ Tecnologias Utilizadas

* **Python:** Linguagem base para análise.
* **Pandas:** Carregamento de dados (ETL), limpeza e manipulação de DataFrames.
* **Matplotlib e Seaborn:** Visualização de dados para criação de gráficos comparativos.
* **Google Colab:** Ambiente de desenvolvimento e documentação.

---
## 🧹 Limpeza e Tratamento de Dados (ETL)
Para garantir a qualidade da análise, os dados brutos passaram por um processo rigoroso de ETL, que incluiu:
- **Tratamento de Valores Ausentes:** Remoção de registros sem a variável alvo (Churn) e preenchimento de faturas vazias.
- **Transformação de Tipos:** Conversão de cobranças lidas como texto para o formato numérico (`float`).
- **Feature Engineering:** Criação da métrica `Cobranca_Diaria` para tangibilizar o custo do serviço ao longo do tempo.
- **Encoding e Padronização:** Tradução de colunas para o português e conversão de categorias binárias (Sim/Não) para `1` e `0`, otimizando o processamento estatístico do dataframe (`df`).

## 📊 Análise Exploratória (EDA) & Insights
A análise exploratória revelou padrões claros sobre o perfil de cancelamento. Os principais achados incluem:

* 🚨 **Contratos Mensais são o maior risco:** Clientes com o plano "Mês a Mês" (Month-to-month) apresentam uma taxa de evasão crítica de **42,7%**. Em contrapartida, contratos anuais retêm a grande maioria da base.
* 📉 **O Paradoxo da Fibra Ótica:** O serviço premium de internet por Fibra Ótica é o que mais perde assinantes (**41,9%** de evasão), indicando um possível problema de qualidade ou precificação frente ao custo-benefício.
* ⏳ **Tempo de Vida Curto:** A mediana de permanência dos clientes que cancelam é de apenas **10 meses**. Reter o cliente no primeiro ano é o maior desafio da empresa.
* 💰 **Fator Financeiro:** O ticket médio de quem evade ($79.65) é visivelmente maior do que o daqueles que permanecem ($64.42).

## 💡 Recomendações Estratégicas
Com base nos dados, as ações recomendadas para a Telecom X incluem:
1. **Revisão Técnica:** Investigar a infraestrutura e o valor percebido do serviço de Fibra Ótica.
2. **Incentivos de Fidelização:** Oferecer benefícios agressivos de *upsell* para migrar clientes do plano mensal para o anual.
3. **Programa de Boas-Vindas:** Criar um acompanhamento intensivo de "Sucesso do Cliente" (CS) nos primeiros 6 meses de contrato.
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
