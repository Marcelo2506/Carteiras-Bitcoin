# Carteiras-Bitcoin
Esse é um projeto de engenharia e análise de dados, onde coletamos, mesclamos e analisamos carteiras de compradores de bitcoin

# Engenharia e Análise de Dados

## Descrição do Projeto
Este projeto tem como objetivo a coleta, processamento e análise de dados financeiros através de processos de ETL (Extração, Transformação e Carga). O foco está na obtenção de informações valiosas sobre a cotação de criptomoedas e taxas de câmbio, utilizando APIs externas. A visualização dos dados é feita através de gráficos interativos, permitindo insights relevantes para tomada de decisões.

## Tecnologias Utilizadas
- **Python**: Linguagem principal para manipulação e análise de dados.
- **Pandas**: Utilizado para manipulação e transformação de dados.
- **Requests**: Responsável por consumir APIs externas.
- **Plotly**: Biblioteca para criação de visualizações interativas.

## Importância do Processo de ETL
O processo de **ETL (Extração, Transformação e Carga)** é fundamental para consolidar dados brutos e convertê-los em informações útis. No contexto deste projeto:
- **Extração**: Dados financeiros são coletados de APIs.
- **Transformação**: Conversão, limpeza e manipulação dos dados para análise.
- **Carga**: Os dados transformados são armazenados e utilizados para visualização e insights.

## Consumo de APIs para Insights e Solução de Problemas
Duas APIs externas são utilizadas para obter informações financeiras em tempo real:
- **[Coinbase API](https://api.coinbase.com/v2/prices/spot)**: Obtém a cotação do Bitcoin (BTC) em diferentes moedas.
- **[AwesomeAPI](https://economia.awesomeapi.com.br/last/USD-BRL)**: Retorna a taxa de câmbio do Dólar (USD) para o Real (BRL).

O consumo dessas APIs permite:
- Monitoramento dinâmico das cotações.
- Correlação entre o preço do Bitcoin e a taxa de câmbio.
- Possibilidade de tomada de decisão baseada em dados atualizados.

## Importância do Conhecimento em Python
Python é essencial para este projeto devido a sua vasta gama de bibliotecas voltadas para análise de dados. Com ele, é possível:
- Automatizar a coleta e processamento de dados financeiros.
- Criar modelos para prever tendências com base em histórico.
- Construir visualizações interativas para interpretação mais intuitiva dos dados.

## Valor Gerado pelo Trabalho com Gráficos
Os gráficos interativos desenvolvidos com **Plotly** permitem uma análise visual mais rica, trazendo vantagens como:
- Facilidade na identificação de padrões e tendências de mercado.
- Melhor compreensão da volatilidade do Bitcoin e câmbio.
- Apresentação visual de dados complexos de forma simplificada.

## Como Executar o Projeto
1. Clone este repositório:
   ```bash
   git clone https://github.com/Marcelo2506/Carteiras-Bitcoin.git
   cd Carteiras-Bitcoin
   ```
2. Instale as dependências necessárias:
   ```bash
   pip install pandas requests plotly
   ```
3. Execute o script principal:
   ```bash
   python main.py
   ```

## Contribuição
Contribuições são bem-vindas! Caso tenha ideias de melhorias ou novos insights, sinta-se à vontade para abrir uma issue ou enviar um pull request.

---
**Autor:** Marcelo Ricardo

