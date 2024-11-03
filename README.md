# Car Sales Dashboard

## Descrição do Projeto

Este projeto é um dashboard de aplicativo web desenvolvido para realizar uma análise exploratória de dados de anúncios de vendas de carros. O objetivo é fornecer uma interface interativa onde os usuários possam visualizar e explorar dados de vendas de carros usando gráficos interativos.

## Funcionalidades

- **Visualização de Dados**: O aplicativo permite a visualização de dados de vendas de carros através de gráficos interativos.
- **Gráficos Disponíveis**:
  - **Histograma**: Visualiza a distribuição dos valores do odômetro dos carros.
  - **Gráfico de Dispersão**: Mostra a relação entre o preço dos carros e o valor do odômetro.
- **Interatividade**: Os usuários podem interagir com os gráficos através de botões ou caixas de seleção para gerar diferentes visualizações.

## Tecnologias Utilizadas

- **Python**: Linguagem de programação utilizada para desenvolver o aplicativo.
- **Pandas**: Biblioteca para manipulação e análise de dados.
- **Plotly Express**: Biblioteca para criação de gráficos interativos.
- **Streamlit**: Framework para desenvolvimento de aplicativos web interativos.

## Como Executar o Projeto

1. **Clone o Repositório**:
```bash
git clone https://github.com/igormerlino/dataTripleten.git
cd dataTripleten
```

2. **Crie e Ative o Ambiente Virtual**:
 ```bash
 python -m venv vehicles_env
 source vehicles_env/bin/activate  # No Windows: vehicles_env\Scripts\activate
 ```

3. **Instale as Dependências**:
```bash
pip install -r requirements.txt
```

4. **Execute o Aplicativo**:
```bash
streamlit run app.py
```

## Estrutura do Projeto
```bash
car-sales-dashboard/
├── README.md
├── app.py
├── vehicles_us.csv
├── requirement.txt
└── notebooks/
    └── EDA.ipynb
└── .streamlit/
    └── config.toml
```

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.