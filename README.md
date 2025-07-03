# 📊 Telecom X – Análise de Evasão de Clientes (Churn)

Análise exploratória de dados da empresa fictícia **Telecom X**, com o objetivo de identificar os principais fatores que levam os clientes a cancelar seus serviços e propor soluções para retenção.

---

## 🧠 Objetivo

- Entender os padrões de evasão de clientes (churn)
- Gerar insights para retenção
- Preparar os dados para modelagem preditiva

---

## 📦 Dados Utilizados

- Fonte: API/JSON
- Registros: 7.032 clientes após limpeza
- Variáveis:
  - Perfil: `Genero`, `Idoso`, `Possui_Parceiro`, `Possui_Dependentes`
  - Contrato: `Tipo_Contrato`, `Fatura_Papel`, `Forma_Pagamento`
  - Serviços: `Tipo_Internet`, `Qtd_Servicos` + serviços específicos
  - Financeiro: `Gastos_Mensais`, `Gastos_Totais`, `Contas_Diarias`
  - Target: `Evasao`

---

## ⚙️ Etapas do Projeto

- ✅ Extração e normalização dos dados
- ✅ Renomeação das colunas para português
- ✅ Tratamento de dados ausentes e inconsistentes
- ✅ Criação de variáveis derivadas
- ✅ Análise exploratória com visualizações
- ✅ Geração de insights de negócios

---

## 📈 Principais Insights

- Contratos mensais → maior evasão
- Pagamento via boleto eletrônico → maior churn
- Clientes com menos serviços → maior risco
- Idosos e clientes sem parceiro → mais propensos ao churn
- Clientes com Fiber Optic → maior evasão em relação a DSL
- Fatura digital → ligeiramente mais evasão que papel

---

## 🛠️ Tecnologias Utilizadas

- Python 3
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Jupyter Notebook

---

## 🚀 Como Executar

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/telecom-churn-analysis.git
