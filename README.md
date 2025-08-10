# Dashboard de Análise de Salários na Área de Dados

Este é um projeto de um dashboard interativo construído com Streamlit para a análise de dados salariais na área de dados. A aplicação permite que os usuários explorem e filtrem os dados para obter insights sobre salários com base em diversos critérios.

## 📊 Visão Geral do Dashboard

O dashboard apresenta uma análise detalhada sobre salários, oferecendo múltiplas visualizações e filtros para uma exploração aprofundada.

## 🚀 Acessando o Dashboard

Você pode acessar e interagir com o dashboard através do seguinte link:

[Acessar o Dashboard de Análise de Salários](https://dashboard-salario-area-de-dados.streamlit.app/)

## ✨ Funcionalidades

*   **Métricas Gerais:** Apresenta o salário médio, salário máximo, o número total de registros e o cargo mais frequente com base nos filtros aplicados.
*   **Filtros Interativos:** Permite filtrar os dados por:
    *   Ano
    *   Nível de Senioridade
    *   Tipo de Contrato
    *   Tamanho da Empresa
*   **Visualizações Dinâmicas:**
    *   **Top 10 Cargos por Salário Médio:** Gráfico de barras horizontais mostrando os cargos com as maiores médias salariais.
    *   **Distribuição de Salários:** Histograma que exibe a frequência das diferentes faixas salariais.
    *   **Proporção dos Tipos de Trabalho:** Gráfico de pizza que mostra a distribuição entre trabalho remoto, híbrido e presencial.
    *   **Salário Médio de Cientista de Dados por País:** Um mapa coroplético e um gráfico de barras que exibem a média salarial para a posição de Cientista de Dados em diferentes países.
*   **Tabela de Dados:** Exibe o conjunto de dados detalhado e filtrado.

## 📂 Estrutura dos Arquivos

O projeto está organizado da seguinte forma:

```
.
├── .gitignore         # Arquivo para ignorar arquivos do Git
├── app.py             # Script principal da aplicação Streamlit
├── dic.py             # Dicionário para tradução de siglas de países
└── requirements.txt   # Lista de dependências Python do projeto
```

*   **`app.py`**: Contém todo o código para a interface do usuário, a lógica de filtragem e a criação dos gráficos do dashboard.
*   **`dic.py`**: Armazena um dicionário Python que mapeia as siglas dos países para seus nomes completos em português.
*   **`requirements.txt`**: Define as bibliotecas Python necessárias para que o projeto funcione corretamente. [2]
*   **`.gitignore`**: Especifica arquivos e diretórios que não devem ser versionados pelo Git, como logs e ambientes virtuais.

## 📈 Fonte dos Dados

Os dados utilizados nesta aplicação são carregados a partir de um arquivo CSV hospedado no GitHub:
`https://raw.githubusercontent.com/sergiocalazans/imersao_dados_com_python_alura_2025/refs/heads/main/dados-imersao-final.csv`

## Tecnologias utilizadas

*   Python 3.13.5
*   Pandas
*   Streamlit
*   Plotly
