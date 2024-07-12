
![bix tecnologia logo (1330 x 150 px)](https://github.com/user-attachments/assets/e597b42e-7313-4454-8048-358ba9d5e495)

# Projeto de Otimização de Planejamento de Manutenção

## Descrição do Projeto
Este projeto aborda um desafio técnico de Data Science com o objetivo de otimizar o planejamento de manutenção de uma empresa de transporte. O foco é prever a probabilidade de falha do sistema de ar dos caminhões, permitindo um planejamento de manutenção mais eficiente e econômico. 

## Etapas do Projeto

### 1. Análise Exploratória de Dados (EDA)
- **Inspeção Inicial**: Carregamento e visualização dos dados de diferentes anos.
- **Distribuição das Classes**: Análise da distribuição das classes nos dados do ano presente e dos anos anteriores.
- **Descrição Estatística**: Cálculo de estatísticas descritivas para compreender as principais características dos dados.

### 2. Limpeza e Preparação de Dados
- **Combinação de DataFrames**: União dos dados dos anos anteriores com os dados do ano presente.
- **Conversão de Tipos de Dados**: Conversão de colunas para tipos numéricos, tratando valores não convertíveis.
- **Configuração de Exibição**: Ajuste das configurações do pandas para melhor visualização dos dados.

### 3. Redução de Dimensionalidade
- **Seleção de Features Numéricas**: Identificação das colunas numéricas para análise e modelagem.
- **Remoção de Colunas Irrelevantes**: Exclusão de colunas que não contribuem para a previsão.

### 4. Construção de Modelos
- **Divisão dos Dados**: Separação dos dados em conjuntos de treinamento e teste.
- **Pipeline de Modelagem**: Construção de um pipeline de pré-processamento e modelagem utilizando `RandomForestClassifier` e `StandardScaler`.

### 5. Avaliação de Modelos
- **Treinamento e Validação Cruzada**: Treinamento do modelo e avaliação com validação cruzada, calculando métricas como acurácia, precisão, recall e F1-score.

### 6. Interpretação de Modelos
- **Importância de Características**: Utilização de técnicas para entender quais características são mais importantes para as previsões do modelo.

### 7. Validação no Conjunto de Teste
- **Previsões e Matriz de Confusão**: Realização de previsões no conjunto de teste e geração da matriz de confusão para análise de desempenho.
- **Avaliação de Impacto Financeiro**: Cálculo dos custos associados a falsos positivos, falsos negativos e verdadeiros positivos, e estimativa do impacto financeiro total.

### 8. Cálculo do Impacto Financeiro
- **Cálculo de Custos**: Estimativa do impacto financeiro baseado nos resultados das previsões, considerando custos de falsos positivos, falsos negativos e verdadeiros positivos.

### 9. Preparação para Produção
- **Planejamento de Implantação**: Planejamento para a implantação do modelo em ambiente de produção, incluindo a criação de pipelines de dados.

### 10. Monitoramento e Manutenção
- **Estratégias de Monitoramento**: Definição de estratégias para monitorar o desempenho do modelo em produção.
- **Critérios para Re-treinamento**: Estabelecimento de critérios para o re-treinamento do modelo conforme necessário.

## Ferramentas e Tecnologias Utilizadas
- **Linguagem de Programação**: Python
- **Bibliotecas**: pandas, numpy, matplotlib, seaborn, scikit-learn, shap
- **Ambiente**: Google Colab

## Como Executar o Projeto
1. Clone este repositório: `git clone <URL do repositório>`
2. Navegue até o diretório do projeto: `cd <nome do diretório>`
3. Abra o notebook no Google Colab ou em outro ambiente Jupyter Notebook.
4. Siga as etapas descritas no notebook para executar o fluxo de trabalho completo.

## Contribuição
Se você quiser contribuir com este projeto, por favor, abra uma issue ou envie um pull request.

## Licença
Este projeto está licenciado sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

![Assinatura email (300 x 100 px) (1330 x 150 px)](https://github.com/user-attachments/assets/0dc00a33-11a4-4933-9008-02e6c8a8cb63)

