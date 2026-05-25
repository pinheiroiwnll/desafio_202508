# 📊 Tratamento e Análise de Dados de Vendas

> Pipeline de ETL e análise exploratória sobre base de vendas de representantes comerciais — do dado bruto ao insight de negócio.

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)

---

## 🎯 Objetivo

Receber uma base de vendas com inconsistências reais e entregá-la tratada, padronizada e analisada — com métricas prontas para tomada de decisão comercial.

---

## 🔄 Pipeline ETL

### 1. Tratamento de Dados
- **Padronização de datas** → formato `YYYY-MM-DD`
- **Normalização de nomes** → representantes e clientes em maiúsculas, sem caracteres extras
- **Conversão numérica** → `Valor Venda` e `Comissão` convertidos para `float`
- **Cálculo de comissão** → `Valor Venda × % Comissão`
- **Padronização de status** → uniformizado para `Pago` / `Em Aberto`
- **Remoção de duplicatas** → mesmo cliente + produto + data + valor
- **Limpeza geral** → espaços, caracteres inválidos e formatos inconsistentes

### 2. Análises Realizadas
| Métrica | Descrição |
|---|---|
| 💰 Total de vendas | Por representante comercial |
| 📈 Total de comissão | Por representante |
| 🎯 Ticket médio | Total Vendas ÷ Nº de Vendas por produto |
| 🔁 Duplicatas | Identificação e remoção de compras repetidas |
| 📋 Status de pagamento | Contagem por categoria (Pago / Em Aberto) |
| 🗺️ Vendas por região | Distribuição geográfica das vendas |

---

## 🗂️ Estrutura do Projeto

```
analise-dados-vendas/
│
├── analise_vendas.xlsx       # Análises e métricas finais
├── dados_tratados.xlsx       # Base tratada e padronizada
├── notebook_analise.ipynb    # Pipeline completo no Jupyter/Colab
└── README.md
```

> ⚠️ Os dados brutos originais não estão no repositório por questões de confidencialidade.

---

## 🛠️ Tecnologias

- **Python** — lógica de tratamento e análise
- **Pandas** — manipulação e transformação de dados
- **Datetime** — padronização e conversão de datas
- **Google Colab** — ambiente de desenvolvimento
- **OpenPyXL** — exportação para Excel

---

## 📌 Aprendizados

Este projeto reforçou na prática que **80% do trabalho em dados é limpeza e padronização**. Antes de qualquer análise, o dado precisa ser confiável — e isso exige atenção a detalhes que passam despercebidos em bases reais.

---

## 👨‍💻 Autor

**Guilherme Pinheiro Serafim**
Analista de Dados | GFT Promotora
[LinkedIn](https://linkedin.com/in/guilherme-pinheiro-527a0927a) · [classespvp@gmail.com](mailto:classespvp@gmail.com)
