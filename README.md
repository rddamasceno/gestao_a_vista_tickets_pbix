# <h1 align="center">Gestão a Vista - Controle de Tickets, Jira e Power BI</h1>

Os dados utilizados neste projeto são dados do sistema Jira, ferramenta para controle de tickets, projetos e backlog. Dados conectados por API do Jira, só que para poder compartilhar eu editei os dados e fiz a tabela em excel para você poder editar de acordo com seus dados.
<br>
<br>
**Metodologia:**

 - Os dados foram importados para o R.
 - Os dados foram limpos e tratados, removendo valores ausentes ou inválidos.
 - Foram criadas diferentes visualizações dos dados usando o ggplot2.


**Impacto da eficiência por tração:**
<br>
![image](https://github.com/rddamasceno/analise_mpg_r/assets/55591959/5b8eecf9-6582-4e55-94c1-f0a66d105d7a)

**Interpretação:**

 - Relação geral: As linhas de tendência indicam uma correlação negativa entre cilindrada e consumo de combustível na estrada. Ou seja, veículos com maior cilindrada tendem a ter menor consumo na estrada.
 - Diferenças entre tipos de tração: Os painéis separados permitem observar que a relação entre cilindrada e consumo pode variar ligeiramente entre veículos com diferentes tipos de tração.
 - Dispersão dos pontos: A dispersão dos pontos indica que existem outros fatores além da cilindrada que influenciam o consumo de combustível, como peso, aerodinâmica e estilo de direção.

**Análise por Ano:**
<br>
![image](https://github.com/rddamasceno/analise_mpg_r/assets/55591959/67f1d23b-16a8-4566-a6a2-7682cfc4deb7)

**Interpretação:**

 - A eficiência do VS dos cilindros aumentou ao longo do ano, de 1999 a 2008
 - No gráfico acima também podemos notar que temos alguns valores discrepantes onde alguns carros possuem cilindros maiores ou iguais a 6, mas ainda apresentam boa eficiência.


<h2 align="left"> 🛠️ Ferramentas:</h2>

 - **Visibilidade e transparência:** Um painel de Power BI pode fornecer uma visão geral clara e concisa do status dos chamados do Jira. Isso pode ajudar os gerentes a acompanhar o desempenho do departamento de TI e identificar quaisquer áreas que precisam de atenção.
 - **Melhoria da comunicação:** Um painel de Power BI pode ser usado para comunicar informações importantes aos funcionários. Isso pode ajudar a garantir que todos estejam na mesma página e trabalhando juntos para resolver problemas.
 - **Aumento da eficiência:** Um painel de Power BI pode ajudar os funcionários a economizar tempo e esforço. Isso ocorre porque eles podem acessar informações importantes de forma rápida e fácil.
 - **Melhoria da tomada de decisão:** Um painel de Power BI pode fornecer aos gerentes dados e insights que podem ajudá-los a tomar decisões mais informadas.
 - **Melhoria da satisfação do cliente:** Um painel de Power BI pode ajudar a melhorar a satisfação do cliente, fornecendo aos clientes informações sobre o status de seus chamados.
