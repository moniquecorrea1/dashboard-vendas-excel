*Descrição do Projeto

Este projeto foi desenvolvido como parte da aula “Criando Dashboard com Excel”, com o objetivo de criar um dashboard de vendas a partir de dados brutos de assinaturas do Xbox Game Pass.

O dashboard tem como finalidade organizar, visualizar e analisar o desempenho de vendas, permitindo identificar receitas por plano, tipo de assinatura, produtos adicionais e impacto da renovação automática.


*Dados Utilizados

Os dados estão localizados na aba Bases da planilha e incluem informações como:

Plano

Tipo de Assinatura (Mensal, Trimestral, Anual)

Renovação Automática

Valor Total

EA Play Season Pass

Minecraft Season Pass

Imagens de ilustração


*Construção do Dashboard

O dashboard foi construído utilizando tabelas dinâmicas e gráficos dinâmicos no Excel, com a coluna Subscription Type como base de filtro principal.
Além das tabelas e gráficos dinâmicos, foram utilizadas segmentações de dados (slicers) para permitir a filtragem interativa das informações, facilitando a análise por tipo de assinatura.

Também foram incluídas imagens ilustrativas relacionadas ao tema (Xbox, EA Play e Minecraft), com o objetivo de melhorar a experiência visual e tornar o dashboard mais intuitivo e atrativo.

* Foram criadas as seguintes tabelas dinâmicas:

- Tabela 1 – Renovação Automática

Nome: tb_annual_total

Linhas: Auto Renewal

Valores: Soma de Total Value
Objetivo: Analisar o impacto da renovação automática na receita total.

- Tabela 2 – EA Play Season Pass

Nome: tbl_easeasonpass_total

Linhas: Plan

Valores: Soma de EA Play Season Pass Price
Objetivo: Identificar a receita gerada pelo EA Play.

- Tabela 3 – Minecraft Season Pass

Nome: tbl_mineseasonpass_total

Linhas: Plan

Valores: Soma de Minecraft Season Pass Price
Objetivo: Identificar a receita gerada pelo Minecraft Season Pass.

- Tabela 4 – Total de Assinantes

Nome: tbl_subscription_total

Valores: Contagem de Subscription Type
Objetivo: Mostrar o total de assinantes pagantes.

- Tabela 5 – Receita por Plano

Nome: tbl_plan_total

Linhas: Plan

Valores: Soma de Total Value
Objetivo: Comparar a receita gerada por cada plano (Core, Standard e Ultimate).


* Resultado

O dashboard final apresenta:

KPIs de vendas

Comparação de receitas por plano

Análise de renovação automática

Receita gerada por produtos adicionais

Essas visualizações permitem análise clara do desempenho de vendas e apoio à tomada de decisões baseadas em dados.


* Como Reproduzir

- Abrir o arquivo Excel

- Acessar a aba Bases (as abas Assets e Cálculos estão ocultas; para reexibi-las, clique com o botão direito do mouse e selecione Reexibir)

- Atualizar as tabelas dinâmicas

- Utilizar os filtros disponíveis no dashboard