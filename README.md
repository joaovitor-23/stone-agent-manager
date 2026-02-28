# 🏢 Stone - Gestão de Agentes (TPV & Novos Clientes)

Uma ferramenta web leve e intuitiva para automatizar o controle diário de performance de agentes em campo. Desenvolvida para substituir processos manuais, permitindo o registro de TPV (Total Processed Volume) e a entrada de novos clientes de forma organizada.

## 🚀 Funcionalidades

* **Gestão de Agentes:** Cadastro e exclusão de agentes com identificação por região/cidade.
* **Registro Diário:** Lançamento de novos clientes e valores de TPV segmentados por semana (S1 a S4).
* **Dashboards em Tempo Real:** * Visualização de totais semanais do mês atual.
    * Resumo individual por agente com histórico de performance.
* **Persistência Local:** Utiliza `localStorage` para manter os dados salvos no navegador, sem necessidade de banco de dados externo inicial.
* **Exportação de Dados:** Função para baixar todos os registros em formato `.csv` para análise no Excel ou Power BI.

## 🛠️ Tecnologias Utilizadas

* **HTML5:** Estrutura semântica.
* **CSS3:** Interface responsiva com foco na identidade visual Stone (Green/Dark mode clean).
* **JavaScript (Vanilla):** Lógica de negócios, cálculos de métricas e manipulação do DOM.

## 📋 Como usar

1.  **Clone o projeto** ou copie o código do arquivo `index.html`.
2.  **Abra o arquivo** em qualquer navegador moderno.
3.  **Cadastre os Agentes:** Comece inserindo o nome e a região no primeiro card.
4.  **Lance os Dados:** No formulário de "Registro Diário", selecione o agente, a semana correspondente e os valores.
5.  **Acompanhe o Resumo:** Os cards inferiores atualizarão automaticamente com o desempenho total e mensal.

---
*Desenvolvido para otimizar fluxos de trabalho manuais e focar no que importa: resultados.*
