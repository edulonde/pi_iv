# Metodologia


# Metodologia

## Visão Geral do Processo

O desenvolvimento do projeto seguiu uma abordagem estruturada de análise de dados, começando com a fase de descoberta (discovery) até a análise descritiva dos dados.

## Fonte de Dados

Os dados foram obtidos através do **Catálogo de Teses e Dissertações** disponibilizado no portal gov.br, que contém informações sobre trabalhos defendidos em programas de pós-graduação do país. 

### Características do Dataset
- **Origem**: Plataforma Sucupira
- **Período**: 2021 a 2023
- **Formato**: CSV e outros formatos
- **Documentação**: Inclui metadados detalhados

## Etapas do Processo

### 1. Discovery (Descoberta)
- Leitura e análise dos metadados
- Compreensão da estrutura dos dados
- Identificação dos campos e seus possíveis valores
- Planejamento das análises necessárias

### 2. Análise Descritiva
Foram realizadas várias análises estatísticas, incluindo:

- Distribuição geográfica dos trabalhos
- Contagem de publicações por área do conhecimento
- Análise de frequência de palavras por área
- Visualização de dados através de diferentes técnicas

### 3. Técnicas de Visualização

Foram utilizadas diferentes técnicas de visualização para representar os dados:

#### Mapas Coropléticos
- Representação da distribuição geográfica
- Visualização de dados por região/estado
- Uso de gradientes de cores para representar quantidade de trabalhos

#### Gráficos de Barras
- Comparação entre categorias
- Visualização de distribuição de trabalhos por estado
- Análise de áreas do conhecimento

#### Nuvem de Palavras (WordCloud)
- Análise de frequência de palavras por área
- Pré-processamento usando biblioteca NLTK
- Remoção de stopwords
- Tokenização de texto

## Ferramentas Utilizadas

- **Python**: Linguagem principal de programação
- **NLTK**: Processamento de linguagem natural
- **WordCloud**: Geração de nuvens de palavras
- **Bibliotecas de Visualização**: Matplotlib, Seaborn

## Próximas Etapas

O projeto continuará com:

1. Construção de algoritmo para predição de área
2. Seleção do modelo mais adequado
3. Fase de inferência e validação
4. Avaliação do modelo

!!! note "Observação"
    A metodologia está em constante evolução, podendo ser adaptada conforme novos insights e necessidades do projeto são identificados.