# 📊 Power BI com DAX – Modelagem Tributária e Segmentação de Clientes

Este repositório contém exemplos práticos de como criar tabelas personalizadas com DAX no Power BI, aplicando conceitos como:

- Enriquecimento de dados com `LOOKUPVALUE`
- Segmentação de clientes com `ADDCOLUMNS` + `IF`
- Simulação de impostos por país
- Agrupamentos dinâmicos com `SUMMARIZE` e `ROLLUP`

---

## 📁 Estrutura do Repositório

| Arquivo                 | Descrição                                                                 |
|--------------------------|---------------------------------------------------------------------------|
| `SalesTaxResumo.dax`     | Tabela com total de vendas por país e alíquota fiscal (`LOOKUPVALUE`)     |
| `KPIClientes.dax`        | Tabela com receita total por cliente e classificação por valor            |
| `TotalFiltrado.dax`      | Agrupamento com múltiplos filtros e totalizadores por país                 |
| `StatusTabela.dax`       | Tabela estática com valores de status (`DATATABLE`)                        |
| `TotalPorCategoria.dax`  | Subtotais de vendas por categoria de produto usando `ROLLUP`              |

---

## ⚙️ Pré-requisitos

- Power BI Desktop instalado
- Modelo de dados contendo:
  - `'Sales Data'` com coluna `Revenue`
  - `'Territory Lookup'` com coluna `Country`
  - `'Customer Lookup'` com `CustomerKey`
  - Tabela `CountryTax` criada via `DATATABLE` (com campos `Country` e `Tax`)

---

## 🚀 Como usar

1. Abra seu arquivo `.pbix`
2. Vá até **Modelagem > Nova Tabela**
3. Copie e cole o código DAX desejado
4. Ajuste os nomes das tabelas se necessário
5. Use a tabela em visuais como Matriz, Tabela ou Slicer

---

## 🧠 Autor

**Eric Vieira**  
📍 Profissional formado em Finanças  
🎓 Pós-graduado em Análise de Dados  
👨‍👧‍👦 Pai de dois  
💡 Apaixonado por ensinar, resolver problemas e explorar o poder dos dados  
🚀 Estudante de Python e entusiasta de soluções inteligentes no Power BI

---

## 📬 Contato

Quer trocar ideia, sugerir melhorias ou apenas bater um papo sobre dados?

https://www.linkedin.com/in/ericvieiradf/

## 📄 Licença

Este projeto é de uso educacional e livre para compartilhar com créditos.  
