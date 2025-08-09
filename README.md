# desafio_202508
Análise de Vendas - Processamento de Dados
Este projeto realiza o pré-processamento e análise de dados de vendas, gerando relatórios consolidados em Excel.

Funcionalidades
Pré-processamento
Padronização de datas para formato YYYY-MM-DD

Normalização de campos de texto (uppercase e remoção de espaços)

Conversão de valores monetários para formato numérico

Cálculo automático de comissões

Remoção de duplicatas

Análise de Dados
Total de vendas por representante

Total de comissão por representante

Ticket médio por produto

Identificação de compras duplicadas

Contagem de vendas por status de pagamento

Total de vendas por região

Como Usar
Pré-requisitos:

Python 3.x

Bibliotecas: pandas, datetime

Execução:

bash
jupyter notebook Desafio_Etapa_1.ipynb
Arquivos:

Entrada: DESAFIO ETAPA 1.xlsx

Saída tratada: dados_tratados.xlsx

Análise final: analise_vendas.xlsx (com múltiplas abas)

Estrutura do Código
Importação de bibliotecas

Carregamento dos dados

Tratamento de dados:

Datas

Campos de texto

Valores monetários

Cálculos:

Comissões

Remoção de duplicatas

Análises:

Métricas por representante, produto e região

Identificação de duplicidades

Exportação dos resultados

Resultados
O script gera um arquivo Excel com 6 abas contendo as análises solicitadas, pronto para visualização e tomada de decisão.

Observação: Certifique-se de que o arquivo de entrada está no mesmo diretório ou ajuste o caminho no código.

