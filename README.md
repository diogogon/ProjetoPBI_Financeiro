<h2 align="center"> Sales and Financial Reports </h2>
<h5 align="right"> Projeto II </h5>
<h5 align="right"> Workshop L. Karpinski: Power BI Experience  </h5>
<h5 align="right"> 23 - 27 de novembro de 2020 </h5>

<p align="justify"><i>Income statement, prof and loss statement ou PnL</i>: demonstração de resultado do exercício ou <b>DRE</b>.<br>
<b>Objetivo</b>: insights sobre o desempenho da empresa por meio de sua situação econômica.</p>

<p align="justify"> Na contabilidade há o tripé decisorial, que contempla a situação financeira, endividamento e a situação econômica, para apoiar as decisões do gestor (Marion, 2009). Com o conjunto de dados disponível seremos capazes de analisar a situação econômica por meio da construção de uma DRE. Fluxo de caixa e balanço patrimonial não foram contemplados.</p>

> Extração dos dados: relatórios do sistema ERP em planilhas .xls.

> Transformação dos dados: editor power query do PBI - automatização do processo. Principais tarefas realizadas:
>>
>> Remoção de linhas vazias, texto por delimitador e colunas duplicadas na base;<br>
>> Definição de cabeçalhos;<br>
>> Alteração do tipo de dado com o local de origem ou pelas configurações regionais (datas e moeda);<br>
>> Remoção do total e subtotais das contas com os valores: como são cálculos, eles serão calculados por medidas.
>> * Os subtotais estão em linhas, vamos eliminá-las de acordo com a “duração” (Lenght) do id deles, ou seja, a quantidade de elementos de cada “célula” da coluna. O total está em coluna. Somente remover.<br>
>>
>> Transformar outras colunas em linhas (unpivot): o conjunto original está em forma de matriz como para os dados clássicos em excel com 3 variáveis: conta, data e valor. No final ficaremos com apenas 3 colunas, em vez de 13, com essas mesmas variáveis. Exemplo:

Conta     | Data1 |Data2|Data3
--------- | ------|-----|-----
Exemplo 1 | R$ 10 |R$ 10|R$ 7
Exemplo 2 | R$ 8  |R$ 7 |R$ 10

Para:

Conta     | Datas |Valor
--------- | ------|-----
Exemplo 1 | Data1 |R$ 10
Exemplo 1 | Data1 |R$  8
Exemplo 1 | Data2 |R$ 10
Exemplo 2 | Data2 |R$  7
Exemplo 2 | Data3 |R$  7
Exemplo 2 | Data3 |R$ 10

3)	Modelagem: 
Raciocínio crítico dos relacionamentos entre tabela fato e dimensões. No projeto, todos 1 para *.

4)	Visuais


O que há de diferente no dashboard do PowerBI Week? Obs: os gifs estão em maior qualidade em tela cheia.

### Home
Criação de uma tela inicial para o relatório com botões dinâmicos¹.

<img src="https://raw.githubusercontent.com/diogogon/myProject_Week_PBI_Karpinski/main/Home.gif">

### Revenue & Margin Analysis
Mudança no template, painel de filtro e painel de dicionário²³.

<img src="https://raw.githubusercontent.com/diogogon/myProject_Week_PBI_Karpinski/main/RevenueandMarginAnalysis.gif">

### Income Statement: 

<img src="https://raw.githubusercontent.com/diogogon/myProject_Week_PBI_Karpinski/main/IncomeStatement.gif">

### Financial simulator:
<p align="justify"> Eliminação de distrações ocasionada principalmente pelo conjunto de dados em tabela, tratamento de cores e organização do <i>layout</i> em busca de um visual mais <i>clean</i>.</p>

<p align="justify"> O visual gráfico "Bullet Chart by OKVIZ" nos permite interpretar de forma mais direta e simples possível com uma comparação de barras sobrepostas de cada cenário. Somado a isso, foi dado ênfase no "KPI" que mostra de fato o resultado da análise e faz uma comparação direta com a meta.</p>

<img src="https://raw.githubusercontent.com/diogogon/myProject_Week_PBI_Karpinski/main/IncomeStatementWIF.gif">

O dashboard completo pode ser visto a seguir:

<iframe width="650" height="400" src="https://app.powerbi.com/view?r=eyJrIjoiMGI2OThlMTgtZTMzOS00ZjUyLTgyYTktZmIwZTc0ZmQ2NjI0IiwidCI6IjkwOTJiNThjLWQxNDctNDE4ZC1hMWYxLWZhN2VhZDNkN2ZiMCJ9" frameborder="0" allowFullScreen="true"></iframe>

<p></p>

### Bibliografia
[¹POWER BI Buttons with animation](https://prathy.com/2020/08/powerbi-buttons-with-animation/) by Prathy Kamasani, August 25, 2020

[²Criando um template do zero](https://www.youtube.com/watch?v=fMrVBEUFCgg) by devAnalytics, Raphael Silva Pacheco, 17 de abr. de 2019 

[³Criando um Menu de Filtros Retrátil](https://www.youtube.com/watch?v=xiNJg7NxC7Y) by devAnalytics, Raphael Silva Pacheco, 22 de abr. de 2019

Marion, José Carlos. Contabilidade empresarial. 15. ed. - São Paulo: Atlas, 2009.

### Autor
*Diogo Gonçalves*
> E-mail: dio.goncalves90@gmail.com

> Github: https://github.com/diogogon

> Linkedin: www.linkedin.com/in/diogogon
