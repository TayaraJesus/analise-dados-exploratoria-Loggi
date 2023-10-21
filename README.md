# Análise Exploratória de Dados de Logística - Loggi

Este projeto é uma análise exploratória de dados da empresa Loggi, uma startup brasileira de tecnologia focada em logística. A Loggi é parceira da EBAC e desempenha um papel fundamental na entrega de mais de 300 mil pacotes diariamente em todo o Brasil. A empresa opera com dezenas de agências e nove centros de distribuição próprios, além de manter parceria com mais de 400 transportadoras.

## Principais Problemas

O objetivo deste projeto é abordar dois dos principais desafios logísticos enfrentados pela Loggi:

1. **Otimização da Rota de Entregas**: Buscamos determinar o caminho mais eficiente para se deslocar entre os pontos de entrega, minimizando tempo e recursos. Isso é fundamental para aumentar a eficiência da entrega de pacotes.

2. **Alocação de Entregas nos Veículos da Frota com Capacidade Limitada**: Garantir que as entregas sejam alocadas de maneira eficaz em veículos com capacidade limitada é essencial para otimizar os recursos e minimizar os custos de transporte.

## Bibliotecas Utilizadas

Para realizar essa análise, utilizamos as seguintes bibliotecas em Python:

```python
import json
import geopy
import geopandas
from geopy.geocoders import Nominatim
from geopy.extra.rate_limiter import RateLimiter

import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt
```

## Como Usar
Para reproduzir ou estender esta análise, siga estas etapas:

1. Clone o Repositório: Faça um clone deste repositório em sua máquina local usando o comando git clone.

2. Instale as Dependências: Certifique-se de ter as bibliotecas Python mencionadas no ambiente em que você pretende executar o projeto. Você pode usar o pip para instalá-las.

3. Execute os Notebooks Jupyter: O projeto pode ser dividido em vários notebooks Jupyter que exploram diferentes aspectos da análise. Execute os notebooks na ordem apropriada para entender a análise passo a passo.

4. Contribua: Sinta-se à vontade para contribuir com melhorias, correções ou insights adicionais para a análise. Basta fazer um fork deste repositório, fazer suas alterações e enviar um pull request.

## Autora
Este projeto foi desenvolvido por Tayara Jesus e faz parte de um trabalho acadêmico colaboração com a EBAC.

Nota: Este projeto é apenas para fins educacionais e de análise de dados. Não está associado à empresa Loggi nem à EBAC. Todas as informações e dados usados aqui são públicos e disponíveis online.
