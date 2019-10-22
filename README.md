A análise em questão foi feita para o [Desafio de Dados 2019](https://desafiodedados.com.br). Ela tem como objetivo avaliar a relação entre nível socioeconômico e distorções de idade-série no âmbito nacional e internacional, utilizando dados do INEP e da UNESCO.

O produto final da análise pode ser visualizado no browser no [Tableau Server](http://tableau.desafiodedados.com.br/views/AnlisedaRelaoEntreNvelSocioeconmicoeDistoresdeIdade-Srie/AnlisedaRelaoEntreNvelSocioeconmicoeDistoresdeIdade-Srie?iframeSizedToWindow=true&:embed=y&:showAppBanner=false&:display_count=no&:showVizHome=no) da competição. Para isso, não é necessária a instalação do Tableau Desktop.

Para reproduzir a análise localmente, é necessária a instalação do Tableau Desktop.

## Instruções para reprodução

Os dados estão armazenados nas pastas: [EdStats_Indicators_Report](https://github.com/mchiriboga/desafio_dados_educacao_2019/tree/master/EdStats_Indicators_Report), [INSE](https://github.com/mchiriboga/desafio_dados_educacao_2019/tree/master/INSE), e [TDI](https://github.com/mchiriboga/desafio_dados_educacao_2019/tree/master/TDI).

Para tratamento dos dados, execute os scripts [education_stats_analysis.Rmd](https://github.com/mchiriboga/desafio_dados_educacao_2019/blob/master/education_stats_analysis.Rmd), [inse_analysis.Rmd](https://github.com/mchiriboga/desafio_dados_educacao_2019/blob/master/inse_analysis.Rmd), e [tdi_analysis.Rmd](https://github.com/mchiriboga/desafio_dados_educacao_2019/blob/master/tdi_analysis.Rmd), em qualquer ordem. Cada script gera um arquivo .csv com os dados tratados.

Uma vez que todos os scripts tenham sido executados, abra o workbook no Tableau Desktop para visualizar a análise. Uma vez que o Tableau não suporta caminhos de arquivo relativos, será necessário atualizar manualmente o caminho de cada um dos data sources quando o workbook for aberto pela primeira vez.
