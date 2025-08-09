Tratamento e Análise de Dados de Vendas

Sobre
Este projeto realiza o tratamento e análise de uma base de vendas de representantes comerciais, corrigindo inconsistências e produzindo métricas solicitadas no desafio técnico.
O dashboard Power BI não foi desenvolvido nesta entrega.

Arquivos
analise_vendas.xlsx – análises e cálculos solicitados.

dados_tratados.xlsx – planilha final tratada.

DESAFIO ETAPA 1.xlsx – base intermediária/processada.

Decisões e Processos
1. Tratamento de Dados
Padronização de datas: convertidas para YYYY-MM-DD.

Normalização de nomes: representantes e códigos de clientes uniformizados (maiúsculas e sem caracteres extras).

Conversão numérica: Valor Venda e Comissão convertidos para float.

Cálculo de Valor Comissão: Valor Venda × Comissão.

Uniformização de status: padronização para “Pago” e “Em Aberto”.

Remoção de duplicatas: linhas com mesmo cliente, produto, data e valor removidas.

Correção de códigos e textos: remoção de espaços, caracteres inválidos e padronização de formato.

2. Análises Realizadas
Total de vendas por representante.

Total de comissão por representante.

Ticket médio por produto (Total de Vendas / Nº de Vendas).

Identificação de compras duplicadas.

Contagem de vendas por status de pagamento.

Total de vendas por região.

3. Ferramentas Utilizadas
Google Colab (Python) para tratamento e análise de dados.

Bibliotecas principais: pandas, datetime.

Funções aplicadas para limpeza, transformação e cálculo, exportando os resultados para Excel.

Observações
Dashboard Power BI não incluído nesta versão.

Dados brutos originais não estão no repositório por confidencialidade.
