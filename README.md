<h2 align="center"> Sales and Financial Reports </h2>
<h5 align="right"> Projeto II </h5>
<h5 align="right"> Workshop L. Karpinski: Power BI Experience  </h5>
<h5 align="right"> 23 - 27 de novembro de 2020 </h5>

Income statement, prof and loss statement, PnL: demonstração de resultados do exercício ou DRE.

<p align="justify"> Para demonstrar essas situações hipotéticas foi proposto KPI's interativos, que tomam como ponto de partida a média total de cada variável (IMC e gastos), travado a alguns filtros de forma intencional: </p>

*Media_**gasto**_regiao = CALCULATE(**AVERAGE**('Seguro de saúde'[Valor do seguro de saúde]),ALL('Seguro de saúde'[Sexo]),ALL('Seguro de saúde'[Região]))*

*Media_**IMC**_faixa = CALCULATE(**AVERAGE**('Seguro de saúde'[IMC]),ALL('Seguro de saúde'[Sexo]),ALL('Seguro de saúde'[Faixa de idades]))*

O dashboard completo pode ser visto a seguir:

<iframe width="650" height="400" src="https://app.powerbi.com/view?r=eyJrIjoiMGI2OThlMTgtZTMzOS00ZjUyLTgyYTktZmIwZTc0ZmQ2NjI0IiwidCI6IjkwOTJiNThjLWQxNDctNDE4ZC1hMWYxLWZhN2VhZDNkN2ZiMCJ9" frameborder="0" allowFullScreen="true"></iframe>

#### Bibliografia
O arquivo original do dataset .csv mais o desafio proposto estão no curso gratuito Microsoft Power BI para Data Science Versão 2.0 oferecido pela DSA. Os arquivos originais são postos de maneira didática e há problemas propositais que simulam a vida real do profissional. Apoie o trabalho.

*OBS: Minha solução já está com todas as modificações que eu julgo correta para a análise dos dados, tanto o dataset como o problema.*

#### Autor
*Diogo Gonçalves*
> E-mail: dio.goncalves90@gmail.com

> Github: https://github.com/diogogon

> Linkedin: www.linkedin.com/in/diogogon
