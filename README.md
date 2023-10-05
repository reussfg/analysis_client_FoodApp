# Análise do Comportamento dos Usuários no Aplicativo de Produtos Alimentícios

## Introdução ao Projeto

Dentro das responsabilidades de nossa startup que vende produtos alimentícios, uma missão crucial é entender o comportamento dos usuários em nosso aplicativo. Nosso objetivo principal é compreender o funil de vendas, discernindo as etapas que os usuários seguem até realizar uma compra. A partir daí, será fundamental identificar os gargalos onde os usuários são mais propensos a abandonar o processo.

Além disso, pretendemos avaliar os resultados de um teste A/A/B, para orientar decisões de design do aplicativo. A questão central é determinar qual fonte, antiga ou nova, é mais eficaz em termos de engajamento e conversão de usuários.

## Descrição dos Dados

Os dados a serem analisados são registros de eventos de usuários. Cada registro é composto pelas seguintes colunas:

- **EventName**: Tipo do evento.
- **DeviceIDHash**: Identificador único do usuário.
- **EventTimestamp**: Timestamp do evento.
- **ExpId**: ID do experimento (246 e 247 são grupos de controle; 248 é o grupo de teste).

## Plano do Projeto

A análise será estruturada nas seguintes etapas:

### 1. Abrir e entender os dados
Início básico, carregando os dados e obtendo uma visão geral dos mesmos.

### 2. Preparação dos Dados
Processamento inicial dos dados, incluindo renomeação, tratamento de dados faltantes e conversões necessárias.

### 3. Análise Exploratória
Investigação profunda para entender a distribuição e frequência dos eventos.

### 4. Estudo do Funil de Eventos
Examinar a sequência que os usuários seguem, identificando possíveis gargalos no processo.

### 5. Avaliação do Teste A/A/B
Compreensão do impacto da mudança de fonte na experiência e conversão do usuário.

Os resultados finais desta análise orientarão as decisões futuras sobre o design e as estratégias de engajamento do aplicativo.

## Importação e Preparação dos Dados

Para começar, carregaremos as bibliotecas necessárias e depois prosseguiremos para a importação e pré-processamento dos dados.

```python
# Carregando bibliotecas
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
from statsmodels.stats.proportion import proportions_ztest

# Continuar com a importação e pré-processamento dos dados...
```
