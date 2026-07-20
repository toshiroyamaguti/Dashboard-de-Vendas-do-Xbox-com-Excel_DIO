# 🎮 Xbox Game Pass Subscriptions Sales - Dashboard

Este repositório contém um projeto de Business Intelligence desenvolvido no **Microsoft Excel**. O objetivo principal é consolidar, tratar e analisar os dados de vendas e assinaturas do ecossistema Xbox (planos Core, Standard e Ultimate), além de metrificar a receita gerada por passes de temporada adicionais e o impacto de cupons de desconto aplicados ao longo do ano de 2024.

---

## 📊 Estrutura do Projeto

O arquivo `dashboard_Vendas_XBox_DIO.xlsx` foi desenvolvido seguindo boas práticas de modularização em BI, dividindo-se em quatro camadas principais:

1. **`A̳ssets`**: Centraliza a identidade visual do projeto, contendo a paleta de cores oficial baseada na marca Xbox (ex: `#9BC848`, `#22C55E`) e elementos gráficos para garantir um design moderno e profissional.
2. **`B̳ases`**: Contém a base de dados bruta contendo o histórico detalhado de 295 registros de clientes. Os principais campos incluem:
   - `Subscriber ID` & `Name`: Identificação e nome do assinante.
   - `Plan`: Tipo do plano adquirido (**Core**, **Standard** ou **Ultimate**).
   - `Start Date`: Data de início da vigência da assinatura.
   - `Subscription Type`: Modelo de recorrência de faturamento (**Monthly**, **Quarterly** ou **Annual**).
   - `Passes Adicionais`: Controle de aquisição de adicionais (*EA Play Season Pass* e *Minecraft Season Pass*).
   - `Coupon Value` & `Total Value`: Valores de descontos aplicados e receita líquida total gerada por usuário.
3. **`C̳álculos`**: Matriz técnica onde os dados brutos são processados através de fórmulas de agregação (como `SOMASE`, `CONT.SE`) e tabelas dinâmicas estruturadas para responder a perguntas de negócio específicas da gestão.
4. **`D̳ashboard`**: Painel visual e interativo de tomada de decisão. Contém indicadores-chave de performance (KPIs), gráficos dinâmicos e **Segmentadores de Dados (Slicers)** que permitem filtrar toda a tela por planos, períodos e status em tempo real.

---

## 🛠️ Recursos e Funcionalidades Utilizadas

- **Modelagem de Dados** com tabelas estruturadas no Excel.
- **Tabelas Dinâmicas (Pivot Tables)** para sumarização rápida e ágil de dados volumosos.
- **Gráficos Dinâmicos e KPIs** integrados para uma experiência fluida de usuário (UX).
- **Segmentadores de Dados (Slicers)** para filtragem dinâmica.
- **Design de Dashboard:** Linhas de grade ocultas, tipografia padronizada e aplicação prática de paleta de cores corporativa.

---

## 🚀 Como Visualizar o Projeto

1. Faça o download do arquivo [`dashboard_Vendas_XBox_DIO.xlsx`](./dashboard_Vendas_XBox_DIO.xlsx) presente neste repositório.
2. Abra o arquivo utilizando o **Microsoft Excel** (versão desktop recomendada para garantir a total compatibilidade dos elementos dinâmicos e segmentadores).
3. Navegue até a aba **`D̳ashboard`** para interagir e explorar os filtros do painel.

---

_Projeto desenvolvido com propósitos de portfólio de análise de dados e business intelligence._
