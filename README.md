# Projeto EBAC - Cientista de Dados Módulo 14

## Pré-processamento de Dados de Churn em Telecom

Autor: **Gabriel Demetrios Lafis**

---

Este projeto faz parte do curso de Formação Cientista de Dados da EBAC e aborda o pré-processamento de uma base realista de clientes de uma empresa de telecomunicações, com o objetivo de preparar os dados para modelagem preditiva de churn (cancelamento de clientes).

### O que você vai encontrar neste repositório

- **Notebook completo** com todas as etapas de limpeza, tratamento de dados faltantes, padronização de categorias e visualização exploratória.
- **Explicações detalhadas** e justificativas para cada decisão de pré-processamento, seguindo as melhores práticas de ciência de dados.
- **Gráficos** que mostram a distribuição dos principais atributos e ajudam a embasar as escolhas de imputação.
- **Código limpo e comentado**, pronto para ser usado como referência em projetos reais de análise de churn.

### Etapas do projeto

1. **Carregamento e ajuste de tipos**  
   Conversão de colunas para tipos adequados (`float`, `int`, `category`), padronização de valores binários e categóricos.

2. **Análise e tratamento de valores faltantes**  
   - Cálculo do percentual de nulos por coluna.
   - Exclusão de linhas sem variável-alvo (`Churn`).
   - Imputação de valores faltantes com estratégias justificadas (mediana, moda, valor padrão).

3. **Padronização de categorias**  
   Correção de inconsistências de grafia e caixa em colunas como `Genero` e `Servico_Internet`.

4. **Padronização dos nomes das colunas**  
   Aplicação do padrão `snake_case` para facilitar a manipulação dos dados.

5. **Visualização exploratória**  
   Gráficos de distribuição e frequência para embasar as decisões de tratamento.

### Como executar

1. Faça o download do notebook e do arquivo de dados `CHURN_TELECON_MOD08_TAREFA.csv`.
2. Execute o notebook em um ambiente Jupyter ou Google Colab.
3. Siga as explicações e adapte para suas próprias análises!

---

**Este projeto demonstra o cuidado necessário na etapa de pré-processamento, fundamental para o sucesso de qualquer modelo de machine learning.**

---

*Gabriel Demetrios Lafis*  
[LinkedIn](https://www.linkedin.com/in/gabrieldemetrioslafis/)
