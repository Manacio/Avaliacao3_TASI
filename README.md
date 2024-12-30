# Avaliacao3_TASI
<<<<<<< HEAD
=======
# Geração de Embeddings com Ollama

Este repositório demonstra como gerar embeddings de texto usando o modelo `mxbai-embed-large` do pacote `langchain_community` com a biblioteca `OllamaEmbeddings`. Embeddings são representações numéricas de texto que capturam o contexto semântico, frequentemente usados em tarefas de NLP (Processamento de Linguagem Natural) como busca, recomendação e análise de sentimentos.

## Objetivo

O objetivo deste código é transformar um texto em um vetor de embeddings que representa seu significado semântico. Cada elemento do vetor é um número que reflete o contexto das palavras e frases do texto fornecido.

## Como Funciona

O código a seguir realiza a geração dos embeddings a partir de um texto:

1. **Texto de entrada**: Um texto é fornecido como entrada. No exemplo, o texto trata de UML (Unified Modeling Language).
2. **Geração de embeddings**: O modelo `mxbai-embed-large` é usado para gerar embeddings para o texto.
3. **Análise do vetor de embeddings**: O código calcula o tamanho do vetor gerado e exibe os primeiros valores.

## Dependências

Este código depende de algumas bibliotecas externas. Para garantir que o ambiente esteja preparado, execute:
1. Primeiro será necessario ter o gerenciador de linguagem de modelo `Ollama`; para isso você precisará execurtar o seguinte codigo em seu terminal:
```bash
ollama run llama3.2:latest 
```
2. Também será preciso ter o gerador de vetor de embeddings. Execute o seguinte código no terminal:
```bash
ollama run mxbai-embed-large:latest
```
3. Por ultimo será nessecario também a biblioteca de código aberto  `langchain`
```bash
pip install langchain_community
```



>>>>>>> 40e922c7c691a94568b9e5e6cf885d9bfb5de6c2
