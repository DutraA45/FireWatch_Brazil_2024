# Análise de Dataset

## Descrição do Projeto
Este projeto visa realizar uma análise exploratória e inferencial de um dataset disponibilizado pelo INPE sobre o clima/tempo com foco em queimadas, utilizando técnicas de Data Science para extrair insights e responder a perguntas de interesse.

## Tecnologias Utilizadas
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scipy
- Statsmodels
- Scikit-learn
- Jupyter Notebook

## Dataset
- **Fonte:** https://www.kaggle.com/datasets/mayaravalliero/fire-watch-brazil-2024/


## Como Executar
1. Clone o repositório:
   ```bash
   git clone https://github.com/DutraA45/FireWatch_Brazil_2024.git

2. Dependências:
    ```bash
    pip install -r requirements.txt

## Análises
- Top 10 estados com maiores precipitações
- Top 10 estados com maiores risco de queimadas
- Evolução do risco de queimadas e média de precipitações ao longo do ano
- Correlação entre dias sem chover e risco de queimadas
- Regressão linear OLS
- Erro Absoluto Médio (MAE)

## Resultados
- A análise realizada mostrou que os níveis de precipitação estão diretamente ligados ao risco de queimadas durante esse ano.
- O mapa de calor de correlação de variaveis trouxe uma visão melhor do nível de influência de cada variavel com o risco de queimadas, tornando mais evidente dentre elas os dias sem chuva.
- Através da correlação entre dias sem chuvas e o risco de queimadas, foi possivel notar que o risco de queimadas tem seu estado agravado pela falta de chuva, mas que não é o único ou principal fator de inflûencia, ou seja, existem outras variáveis também influenciando

## Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir uma issue ou enviar um pull request.

## Próximos Passos
Implementação da biblioteca Geopandas
