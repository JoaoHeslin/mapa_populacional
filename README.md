# Mapa Populacional das Cidades da Paraíba

Este projeto tem como objetivo criar uma visualização interativa de um mapa populacional para várias cidades do estado da Paraíba, Brasil. Utilizando a biblioteca Plotly, o mapa mostra a distribuição populacional em diferentes localidades com uma representação visual intuitiva.

## Conteúdo

1. *Introdução*
   - O script exibe um mapa de densidade populacional utilizando coordenadas geográficas e dados de população para cidades selecionadas.

2. *Bibliotecas Utilizadas*
   - pandas: Para manipulação e organização dos dados.
   - plotly.express e plotly.io: Para criação e exibição de gráficos interativos.

3. *Dados*
   - O DataFrame contém as seguintes colunas:
     - Cidade: Nome da cidade.
     - UF: Unidade Federativa (estado).
     - Latitude: Latitude da cidade.
     - Longitude: Longitude da cidade.
     - População: População da cidade.

4. *Visualização*
   - *Mapa Populacional*: Criado com px.density_mapbox, que exibe a intensidade da população em diferentes áreas geográficas.
     - *Parâmetros do Mapa*:
       - lat e lon: Coordenadas das cidades.
       - z: Valor da população para ajustar a densidade.
       - radius: Raio dos pontos de densidade no mapa.
       - center: Centro inicial do mapa.
       - zoom: Nível de zoom inicial.
       - mapbox_style: Estilo visual do mapa (definido como "stamen-terrain").
