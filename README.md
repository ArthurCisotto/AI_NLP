# Análise de Aceitação de Artigos Científicos

Este projeto analisa um dataset de artigos científicos para prever a aceitação com base no conteúdo dos abstracts. Utilizamos técnicas de processamento de linguagem natural (NLP) e aprendizado de máquina para realizar esta análise.

Para uma descrição detalhada do projeto, metodologia e resultados, por favor consulte o arquivo `artigo.pdf`.


## Funcionalidades

1. Carregamento e pré-processamento de dados do dataset PeerRead
2. Análise exploratória dos dados
3. Implementação de um pipeline de classificação usando TF-IDF e Regressão Logística
4. Avaliação do impacto do tamanho do dataset no desempenho do modelo
5. Análise de tópicos usando LDA (Latent Dirichlet Allocation)
6. Implementação de um classificador de duas camadas

## Requisitos

- Python 3.7+
- Jupyter Notebook
- Bibliotecas listadas em `requirements.txt`

## Instalação

1. Clone este repositório:
   ```
   git clone https://github.com/seu-usuario/nome-do-repositorio.git
   cd nome-do-repositorio
   ```

2. Crie um ambiente virtual (opcional, mas recomendado):
   ```
   python -m venv venv
   source venv/bin/activate  # No Windows use `venv\Scripts\activate`
   ```

3. Instale as dependências:
   ```
   pip install -r requirements.txt
   ```

## Uso

1. Certifique-se de que o dataset PeerRead está na pasta `data/` do projeto.

2. Inicie o Jupyter Notebook:
   ```
   jupyter notebook
   ```

3. Abra o notebook `project.ipynb` no navegador.

4. Execute as células do notebook sequencialmente para realizar as análises e gerar os resultados.

## Estrutura do Projeto

- `project.ipynb`: Notebook Jupyter contendo todo o código e análises
- `data/`: Diretório contendo o dataset PeerRead
- `requirements.txt`: Lista de dependências do projeto
- `artigo.pdf`: Artigo detalhando o projeto, metodologia e resultados

## Resultados

O notebook gera várias análises e visualizações, incluindo:
- Distribuição de papers por dataset
- Taxa de aceitação por dataset
- Avaliação do classificador
- Análise do impacto do tamanho do dataset no desempenho do modelo
- Modelagem de tópicos e sua relação com a aceitação de papers
