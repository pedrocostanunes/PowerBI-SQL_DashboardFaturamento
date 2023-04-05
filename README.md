# Dashboard de Faturamento | SQL e PowerBI 
*Nota: [clique aqui](https://app.powerbi.com/groups/me/reports/8cdb7394-879d-4d12-ae88-30047a91ad19/ReportSectionefaec0dcc3cc5f106285?ctid=0343411f-9443-415f-a0fb-1d1ab82ca677) para visualizar o Dashboard.*

Olá! 

Bem-vinde a este projeto de portfólio que engloba queries em **SQL** e montagem de dashboard no **PowerBI**. O objetivo do projeto foi montar uma visualização rápida e prática sobre faturamento de e-commerce no Brasil, com filtros por estado e por ano. O dataset utilizado foi "*Brazilian E-Commerce Public Dataset by Olist*", que está disponível no Kaggle através [deste link](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce). Este conjunto de dados concentra informações sobre o desempenho do e-commerce brasileiro entre os anos 2016 e 2018, sendo este também o intervalo de tempo dos dados deste projeto. 

Dividi este trabalho em duas etapas, sendo a primeira a criação de um database e tabelas de fato no **SQL**, finalizando com uma consulta realizada para capturar apenas os dados necessários para o dashboard. E a segunda, uma montagem do painel de faturamento no **Power BI**, importando os dados das queries e transformando-as em gráficos para vizualização.

## 1. SQL
Utilizei o Microsoft SQL Server para importar os arquivos .csv baixados do Kaggle, criar tabelas as tabelas de fato e criar a consulta. Você pode conferir estas etapas neste repositório através do arquivo [[SQL]tabelas_fato_select_powerBI.sql](https://github.com/pedrocostanunes/PowerBI-SQL_DashboardFaturamento/blob/main/%5BSQL%5Dtabelas_fato_select_powerBI.sql). 

## 2. Power BI
Conforme explicado na introdução deste README, utilizei o Power BI para criar um painel que explicite de forma bem direta e clara os KPIs sobre faturamento de vendas em e-commerce, utilizando filtros temporais e por localidade no Brasil. Para visualizar o dashboard, **você pode [clicar aqui](https://app.powerbi.com/groups/me/reports/8cdb7394-879d-4d12-ae88-30047a91ad19/ReportSectionefaec0dcc3cc5f106285?ctid=0343411f-9443-415f-a0fb-1d1ab82ca677)**, ou baixar o arquivo .pbix que está **[neste repositório]([http://](https://github.com/pedrocostanunes/PowerBI-SQL_DashboardFaturamento/blob/main/%5BPOWERBI%5Ddashboard_faturamento.pbix))**.

- Também esiste a opção rápida de um [preview do dashboard](https://github.com/pedrocostanunes/PowerBI-SQL_DashboardFaturamento/blob/main/preview_dashboard.png) (imagem estática apenas) para quem tem pressa.
- Disponibilizei no repositório o [backgorund do dashboard](https://github.com/pedrocostanunes/PowerBI-SQL_DashboardFaturamento/blob/main/bg_dashboard.png), criado por mim no Figma.

## Tecnologias Utilizadas neste Projeto

- [Microsoft Power BI](https://powerbi.microsoft.com/pt-br/)
- [Microsoft SQL Server](https://www.microsoft.com/pt-br/sql-server/sql-server-2019)
- [Figma](https://www.figma.com/)

Vale ressaltar: gosto muito de feedbacks e insights de como posso melhorar meus projetos. Vou ficar muito feliz em receber suas observações e colaborações! Fique à vontade para me contatar em caso de dúvidas ou sugestões.

No mais, divirta-se e boa leitura! 😊
