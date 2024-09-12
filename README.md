# Case de Processo Seletivo: Análise de Viabilidade de Novo Modelo de Prevenção de Fraudes

Este repositório contém o case desenvolvido para o processo seletivo de Data Scientist no **Grupo Boticário**, onde foi realizada uma análise de viabilidade financeira e técnica para a adoção de um novo modelo de prevenção de fraudes. O estudo inclui uma análise detalhada das métricas de performance do modelo atual e do modelo proposto, com foco em métricas como taxa de aprovação, impacto financeiro e escalabilidade.

## Estrutura do Repositório

- **Relatório**: Contém uma análise detalhada dos dados, cálculo do ROI e recomendações estratégicas. O relatório completo está disponível no arquivo [relatorio_gb_tech.pdf](link).
- **Jupyter Notebook**: Código-fonte usado para a análise descritiva, visualizações e cálculo das métricas. O notebook pode ser acessado diretamente [neste link](https://colab.research.google.com/drive/1dfolUTaFLeQ1-wN1KsWU9ySSQ7MoSmPD?usp=sharing).

## Descrição do Case

O objetivo era avaliar a viabilidade da implementação de uma nova ferramenta de prevenção de fraudes, comparando seu desempenho com o modelo interno atualmente utilizado pela empresa. A nova ferramenta prometia um aumento de 4.4 p.p. na taxa de aprovação de pedidos, ao custo de R$6 por transação avaliada.

### Metodologia

1. **Análise Descritiva**: Foram utilizadas bibliotecas do Python como Pandas, Numpy e Matplotlib para explorar e comparar as principais métricas dos dois modelos:
   - Pedidos Aprovados e Reprovados
   - Taxa de Aprovação de Fraudes
   - Comparação entre o valor total de pedidos aprovados.

2. **Análise de Impacto Financeiro**: Foi calculado o retorno sobre o investimento (ROI), considerando o custo adicional do novo modelo e o valor gerado pela maior taxa de aprovações.

3. **Análise de Escalabilidade**: Estudou-se o comportamento do modelo em diferentes cenários de crescimento de pedidos, para entender como o impacto financeiro se alteraria em larga escala.

### Resultados Principais

- A nova ferramenta proporcionou um aumento de **4.7 p.p.** na taxa de aprovação de pedidos, superando a proposta inicial.
- O cálculo do ROI demonstrou que, mesmo com o custo adicional por transação, o novo modelo é financeiramente vantajoso, com um retorno de **56.9%** sobre o investimento.
- A análise de escalabilidade indicou que, com o aumento do volume de pedidos, o impacto positivo do novo modelo se intensifica.

## Tecnologias Utilizadas

- **Python** (Pandas, Numpy, Matplotlib)
- **Google BigQuery** para tratamento e consulta de dados.
- **Jupyter Notebook** para desenvolvimento do código.

## Como Utilizar

1. Faça o download ou clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   ```

2. Abra o notebook no seu ambiente local ou diretamente no Google Colab [aqui](https://colab.research.google.com/drive/1dfolUTaFLeQ1-wN1KsWU9ySSQ7MoSmPD?usp=sharing).

3. Execute as células para reproduzir os resultados da análise.
