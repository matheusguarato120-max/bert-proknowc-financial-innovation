# bert-proknowc-financial-innovation
Python scripts using BERT (paraphrase-multilingual-MiniLM-L12-v2) for semantic screening and filtering in a ProKnow-C systematic review of innovation and corporate financial performance.

## BERT Semantic Screening for ProKnow-C Systematic Review
Este repositório contém o ambiente integrado em Python utilizado para a automação da triagem semântica e metodológica do meu Trabalho de Conclusão de Curso (TCC) na Universidade Federal de Uberlândia (UFU).

## Objetivo do Projeto
O algoritmo utiliza a arquitetura `paraphrase-multilingual-MiniLM-L12-v2` (BERT) para calcular a similaridade de cosseno e filtrar o volume massivo de artigos da Web of Science. O foco é selecionar o portfólio bibliográfico ideal sobre o ecossistema de **Inovação Corporativa e Desempenho Financeiro ao nível da firma**.

## Fluxo do Funil Bibliométrico
O arquivo `SYSTEMATIC_REVIEW_SEMANTIC_SCREENING_VIA_BERT_(PROKNOW_C).ipynb` executa o pipeline em dois blocos sequenciais:
1. Títulos: Aplica uma nota de corte de 0,50 para eliminar ruídos temáticos e artigos fora do escopo corporativo/financeiro.
2. Resumos: Aplica uma nota de corte restrita de 0,55 focada em identificar metodologias empírico-quantitativas e modelos econométricos.

## Como Executar
O projeto foi desenvolvido para rodar de forma 100% gratuita na nuvem utilizando a GPU do Google Colab. 
1. Abra o arquivo `.ipynb` neste repositório.
2. Clique no botão de execução para instalar as dependências (`sentence-transformers`, `pandas`, `openpyxl`, `tqdm`).
3. Faça o upload das suas planilhas nos blocos correspondentes quando solicitado pela interface do Colab.
