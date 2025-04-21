# Dashboard Interativo - Previsão da Cotação do Dólar (USD/BRL)

Este projeto apresenta um dashboard desenvolvido com Dash e Plotly para visualizar dados históricos da cotação do dólar frente ao real e a previsão dos próximos 3 meses utilizando modelos de machine learning (LSTM).

## Funcionalidades

- Exibição de dados históricos da cotação do dólar.
- Visualização das previsões futuras com base em modelos LSTM.
- Interface interativa com zoom, hover e destaque de pontos.

## Tecnologias Utilizadas

- Python
- Dash
- Plotly
- Pandas
- Scikit-learn
- LSTM (modelo treinado previamente)

## Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/dashboard-previsao-dolar.git
   cd dashboard-previsao-dolar
Instale as dependências:

bash
Copiar
Editar
pip install -r requirements.txt
Coloque os arquivos dolar_real_historico.csv e previsao_dolar_3_meses.csv na raiz do projeto.

Execute o servidor:

bash
Copiar
Editar
python app.py
Acesse http://127.0.0.1:8050 no seu navegador.
