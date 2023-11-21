# relatorio-tecnico-PUC

## Descrição:
Este repositório contém os notebooks com códigos desenvolvidos para escrita do relatório técnico final, requisito obrigatório para a conclusão da especialização em Inteligência Artificial
e Aprendizado de Máquina na PUC. O trabalho consistiu no estudo e classificação de fake news em português, com base no corpus de notícias originado de um trabalho desenvolvido no Núcleo Interinstitucional de Linguística
Computacional (NILC). O corpus está disponível em um repositório da plataforma GitHub e pode ser encontrado neste [link](https://github.com/roneysco/Fake.br-Corpus).

## Arquivos e objetivos:
 - *obtencao_transformacao.ipynb*: Leitura dos arquivos ".txt" presentes nas pastas, extração da informações desejadas, união e transformação em um arquivo ".csv" único.
 - *tratamento_preprocessamento.ipynb*: Avaliação de qualidade dos dados, limpeza, tratamento e pré-processamento de dados.
 - *analise_exploracao.ipynb*: Análise exploratória dos dados.
 - *preparacao_dados_treino*: Preparação dos dados para treino, validação e teste dos modelos Naive Bayes (utilizado como baseline), LGBM, Bi-LSTM e BERT (transfer learning do [modelo Bertimbau](https://huggingface.co/neuralmind/bert-base-portuguese-cased))
