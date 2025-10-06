# Projeto Mapa de Calor - Vendas de Imóveis na Bahia

Este projeto apresenta um mapa de calor geográfico interativo, utilizando Python e Plotly, para visualizar a quantidade hipotética de vendas de imóveis em cidades do estado da Bahia.

## Estrutura do Projeto

- `mapa_de_calor.ipynb`: Notebook principal com todo o código para geração dos dados e visualização do mapa.
- `README.md`: Este arquivo de documentação.

## Tecnologias Utilizadas

- Python 3
- Pandas
- Plotly Express

## Como funciona

O notebook cria uma base de dados fictícia com as seguintes cidades baianas:
- Feira de Santana
- Salvador
- Alagoinhas
- Paulo Afonso
- Juazeiro
- Vitória da Conquista

Para cada cidade, são informadas as coordenadas geográficas e a quantidade de imóveis vendidos em um mês (dados hipotéticos).

O mapa de calor é gerado com o Plotly Express, exibindo cada cidade como um ponto no mapa, onde o tamanho do ponto representa o volume de vendas.

## Como executar

1. Instale as dependências:
   ```sh
   pip install pandas plotly
   ```
2. Abra o arquivo `mapa_de_calor.ipynb` no Jupyter Notebook ou no Visual Studio Code.
3. Execute todas as células para visualizar o mapa interativo.

## Exemplo de visualização

![Exemplo de mapa de calor](mapa_de_calor.png)

## Licença

Este projeto é apenas para fins educacionais e demonstração.

---

Qualquer dúvida ou sugestão, fique à vontade para abrir uma issue!