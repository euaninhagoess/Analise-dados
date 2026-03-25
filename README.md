# ​Análise Exploratória de Dados: Crédito Bancário 
​Este projeto consiste na exploração inicial de um conjunto de dados contendo 30.000 registos de clientes bancários. O objetivo foi validar a integridade dos dados, entender o perfil dos clientes e identificar padrões de crédito utilizando a biblioteca Pandas.

## Ferramentas Utilizadas
​Python   
​Pandas: Manipulação e análise de dados   
Google Colab: Ambiente de desenvolvimento na nuvem

### Etapas da Análise
​1. Preparação e Carga
​O arquivo foi carregado a partir do Google Drive e convertido num DataFrame (df) para facilitar a manipulação.

​2. Inspeção de Estrutura
​Foram utilizados comandos para entender a dimensão do problema:
​Colunas: 25 características diferentes.
​Linhas: 30.000 amostras de clientes.
​Tipos de Dados: Identificação de variáveis numéricas (int64) e textuais (object).

​3. Investigação de Perfil (Filtros)
​Realizei uma busca segmentada para encontrar clientes com o seguinte perfil:
​Idade: Acima de 50 anos.
​Limite de Saldo: Acima de 20.000.
​Resultado: Foram encontrados **2.033** clientes que se encaixam nesta categoria de alta estabilidade e crédito.

​4. Qualidade dos Dados
​Verificação de dados nulos (isnull().sum()), confirmando que o dataset está completo e pronto para modelagem, sem necessidade de limpeza imediata
