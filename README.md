<h2 align="center"> Sales and Financial Reports </h2>
<h5 align="right"> Projeto II </h5>
<h5 align="right"> Workshop L. Karpinski: Power BI Experience  </h5>
<h5 align="right"> 23 - 27 de novembro de 2020 </h5>

<p align="center"> <img src="https://github.com/diogogon/projeto-1/blob/main/Text.png">

- [X] Se for homem, na faixa de 20 a 59 anos e da região Sudeste, o gasto é maior ou menor que a média de gastos da região?

<p align="justify"> Para demonstrar essas situações hipotéticas foi proposto KPI's interativos, que tomam como ponto de partida a média total de cada variável (IMC e gastos), travado a alguns filtros de forma intencional: </p>

*Media_**gasto**_regiao = CALCULATE(**AVERAGE**('Seguro de saúde'[Valor do seguro de saúde]),ALL('Seguro de saúde'[Sexo]),ALL('Seguro de saúde'[Região]))*

*Media_**IMC**_faixa = CALCULATE(**AVERAGE**('Seguro de saúde'[IMC]),ALL('Seguro de saúde'[Sexo]),ALL('Seguro de saúde'[Faixa de idades]))*

<p align="center"> <img src="https://github.com/diogogon/projeto-1/blob/main/KPI_IMC.png"> <img src="https://github.com/diogogon/projeto-1/blob/main/KPI_Gasto.png">

O dashboard completo pode ser visto a seguir:

<p align="center"> <img src="https://github.com/diogogon/projeto-1/blob/main/Visual_geral.png">

O arquivo .pbix do dashboard:
[projeto I PBI: Análise de gastos na saúde](https://app.powerbi.com/view?r=eyJrIjoiMGI2OThlMTgtZTMzOS00ZjUyLTgyYTktZmIwZTc0ZmQ2NjI0IiwidCI6IjkwOTJiNThjLWQxNDctNDE4ZC1hMWYxLWZhN2VhZDNkN2ZiMCJ9)

<iframe width="580" height="480" src="https://app.powerbi.com/view?r=eyJrIjoiMGI2OThlMTgtZTMzOS00ZjUyLTgyYTktZmIwZTc0ZmQ2NjI0IiwidCI6IjkwOTJiNThjLWQxNDctNDE4ZC1hMWYxLWZhN2VhZDNkN2ZiMCJ9" frameborder="0" allowFullScreen="true"></iframe>


#### Bibliografia
O arquivo original do dataset .csv mais o desafio proposto estão no curso gratuito Microsoft Power BI para Data Science Versão 2.0 oferecido pela DSA. Os arquivos originais são postos de maneira didática e há problemas propositais que simulam a vida real do profissional. Apoie o trabalho.

*OBS: Minha solução já está com todas as modificações que eu julgo correta para a análise dos dados, tanto o dataset como o problema.*

#### Autor
*Diogo Gonçalves*
> E-mail: dio.goncalves90@gmail.com

> Github: https://github.com/diogogon

> Linkedin: www.linkedin.com/in/diogogon
