# BWE: Bank Word Embeddings ptBR

## Geral

A tarefa de Processamento de Linguagem Natural escolhida foi o cálculo de similaridade entre palavras do domínio específico bancário, e foi utilizada a arquitetura Continuous Bag Of Words como solução.

O problema considerado foi a estimativa de similaridade semântica entre palavras de um domínio específico, o que pode ser interessante para processos de obtenção de conhecimento a partir de textos em linguagem natural (e.g., estruturando o conhecimento presente nestes dados não-estruturados).

O corpus utilizado foi o glossário simplificado de termos financeiros do Banco Central (Bacen).
Foram utilizadas as bibliotecas NLTK e gensim.

Foram comparados dois word embeddings de escopo geral para o português (http://nilc.icmc.usp.br/embeddings), de modelos CBOW e Glove 50 dimensões com o modelo específico desenvolvido CBOW com 100 dimensões na tarefa de similaridade do cosseno entre os \textit{word embeddings} da palavra 'banco' e outras relacionadas ao domínio bancário.

## Arquivos disponíveis

Relatório em PDF e TEX, código do tipo Python notebook (desenvolvido no ambiente Google Colab).
