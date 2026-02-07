# Amostragem dos Índices da Bolsa Brasileira (Ibovespa, SMALL, IBrA)

![Imagem de Capa](https://github.com/mhirokitomida/imagens/blob/main/github-mark.png?raw=true)  

## Estudo Didático de Amostragens de Índices de Ações

Este projeto realiza **amostragens das carteiras de ações** de índices brasileiros: **Ibovespa**, **SMALL** e **IBrA**, com o objetivo de estudar **técnicas de amostragem** no contexto do mercado financeiro. 

Para fins de comparação visual, o saldo e o retorno (medido pela variação do saldo) das carteiras são calculados a partir de uma **simulação de investimento inicial de R$ 100.000**, dividido **igualmente entre todas as ações** do índice ou da amostra correspondente. 

⚠️ Este projeto é **apenas didático**. Não tem objetivo de montar carteiras rentáveis nem avaliar riscos ou performance — tanto dos índices quanto das amostras.  
Além disso, a amostragem normalmente **não é necessária** para esses índices, já que eles contêm relativamente poucas ações; foi realizada aqui **somente para fins didáticos**, a fim de estudar técnicas de amostragem no mercado financeiro.

## 🔧 Principais Funcionalidades

- Extração das ações dos índices do site da B3 via **webscraping**, com **processamento paralelo**.
- Geração de diferentes tipos de amostras:
  - Aleatória simples, Sistemática, Por grupo e Estratificada
- Cálculo de métricas para cada índice e suas amostras:
  - **Saldo acumulado** e **Retorno diário**
- Visualizações interativas com **Plotly**:
  - Comparação entre índices e suas amostras
  - 
## 📊 HTML (Python)

Confira o HTML com as comparações dos Índices x Amostragens:

<a href="https://mhirokitomida.github.io/amostragem_indice_bolsa_brasileira/">
  <img src="https://github.com/mhirokitomida/imagens/blob/main/grafico_colorido.png?raw=true" alt="Índices X Amostras" width="40">
  Índices X Amostras
</a>
