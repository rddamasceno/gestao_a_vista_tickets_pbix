<h1 align="center">Gestão à Vista - Controle de Tickets, Jira e Power BI</h1>

Os dados utilizados neste projeto são dados do sistema Jira, ferramenta para controle de tickets, projetos e backlog. Dados conectados pela API do Jira.
<br>
<br>
**Metodologia:**

 - Importei os dados para o Power BI utilizando a API do JIRA.
 - Realizei a limpeza e tratamento dos dados, removendo valores ausentes ou inválidos e normalizando.
 - Desenvolvi diversas visualizações dos dados utilizando os gráficos disponíveis no Power BI.


**Tela Principal:**
<br>
![Tela1](https://github.com/rddamasceno/gestao_a_vista_tickets_pbix/assets/55591959/51582ab8-15f3-41ee-af5e-4bd87e0771ca)

**Interpretação:**

 - **Relatório de Tickets por Status e Departamento:** Apresentaremos uma relação dos tickets organizados por status e departamento.
 - **Quantidade Acumulada de Tickets no Ano:** Mostraremos a quantidade total de tickets acumulados ao longo do ano.
 - **Tickets nos Últimos 3 Meses:** Quantidade de tickets nos últimos 3 meses, indicando seus respectivos status. Destacamos que os tickets de meses anteriores devem estar encerrados, evidenciando a conclusão dos chamados e garantindo a eficiência nos processos.

**Indicadores Macro de Tickets:**

 - **Tickets Abertos no Dia:** Quantidade de tickets abertos no dia.
 - **Tickets Abertos no Mês:** Quantidade de tickets abertos no mês.
 - **Tickets Concluídos no Mês:** Quantidade de tickets concluídos no mês.
 - **Total de Tickets no Ano:** Número total de tickets registrados no ano.

**Drill Through:**
<br>
![image](https://github.com/rddamasceno/gestao_a_vista_tickets_pbix/assets/55591959/da06c7a3-07e9-4779-8e38-19c4f3d83681)

 - **Drill Through para análise detalhada dos dados:** A funcionalidade de "Drill Through" simplifica a compreensão dos dados. Com um simples clique, você pode ver detalhes mais específicos por trás das visões apresentadas. Isso proporciona maior liberdade, permitindo uma análise fácil e clara dos dados

**Modelagem dos dados:**
<br>
![Tela3](https://github.com/rddamasceno/gestao_a_vista_tickets_pbix/assets/55591959/619145f4-2afb-4288-985f-c8a9768c4bd0)

 - **Conceito da Modelagem:** Relacionamento Muitos para Um, entre a dimensão tempo (dCalendario) e fChamados, poderia ser criadas outras tabelas, como por exemplo, pegar a informação de gestores das equipe e montar uma visão onde mostre os responsaveis dos tickets e seus superiores, outra tabela de status e macro status, etc.

<h2 align="left"> 🛠️ Objetivos:</h2>

 - **Visibilidade e transparência:** Um painel de Power BI pode fornecer uma visão geral clara e concisa do status dos chamados do Jira. Isso pode ajudar os gerentes a acompanhar o desempenho do departamento de TI e identificar quaisquer áreas que precisam de atenção.
 - **Melhoria da comunicação:** Um painel de Power BI pode ser usado para comunicar informações importantes aos funcionários. Isso pode ajudar a garantir que todos estejam na mesma página e trabalhando juntos para resolver problemas.
 - **Aumento da eficiência:** Um painel de Power BI pode ajudar os funcionários a economizar tempo e esforço. Isso ocorre porque eles podem acessar informações importantes de forma rápida e fácil.
 - **Melhoria da tomada de decisão:** Um painel de Power BI pode fornecer aos gerentes dados e insights que podem ajudá-los a tomar decisões mais informadas.
 - **Melhoria da satisfação do cliente:** Um painel de Power BI pode ajudar a melhorar a satisfação do cliente, fornecendo aos clientes informações sobre o status de seus chamados.

<h2 align="left"> 📢 Obs:</h2>

 - Coloquei os arquivos do projeto anexados no repositório, salvei os dados que estavam vindo pela API em um arquivo Excel para facilitar o uso pessoal. Os dados são aleatórios e não representam informações reais.
