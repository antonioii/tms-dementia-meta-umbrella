# Uma revisão guarda-chuva de metanálises avaliando a eficácia da estimulação magnética transcraniana em demências

Este repositório reúne o resumo (abstract) da dissertação de mestrado e todos os materiais complementares (tabelas, bancos de dados e códigos) utilizados no estudo de revisão guarda-chuva de metanálises sobre a eficácia da estimulação magnética transcraniana repetitiva (EMTr) em demências neurodegenerativas, com foco principalmente na doença de Alzheimer.

A dissertação foi desenvolvida no Instituto de Psiquiatria (IPUB) da Universidade Federal do Rio de Janeiro (UFRJ), no âmbito do Mestrado em Psiquiatria. A síntese estatística do tipo meta-umbrella e as análises associadas foram conduzidas com auxílio do software R, planilhas eletrônicas e a linguagem Python.

## Resumo / Abstract

- Resumo  
  As doenças neurodegenerativas em idosos configuram um crescente problema de saúde global, sendo a doença de Alzheimer (DA) a principal causa. A estimulação magnética transcraniana repetitiva (EMTr) surgiu como intervenção não farmacológica promissora para sintomas cognitivos e comportamentais. Esta revisão guarda-chuva de metanálises avaliou a eficácia da EMTr em demências neurodegenerativas. O estudo seguiu as diretrizes PRISMA e foi registrado no PROSPERO (CRD42023489100). A busca sistemática ocorreu nas bases PubMed/MEDLINE, Embase, SciELO, Web of Science e Cochrane CENTRAL. Dois revisores realizaram, de forma independente, a seleção dos estudos, a extração de dados, a avaliação de qualidade e o risco de viés. As ferramentas AMSTAR-2 e ROBIS avaliaram a qualidade metodológica e o risco de viés, respectivamente, enquanto a abordagem GRADE verificou a certeza da evidência. A síntese estatística tipo meta-umbrella foi conduzida com auxílio do software R. Dos 2.288 registros identificados, 16 artivos de revisão contendo 33 gráficos de metanálises abarcando ao todo 57 ensaios clínicos randomizados sobre DA foram incluídas. Na população avaliada para desfechos cognitivos e comportamentais combinados, destes 16 estudos (n = 350), a EMTr apresentou efeito pequeno, mas significativo (g = 0,40; IC95%: 0,19–0,60; I² = 42,9%), com certeza moderada. Para apenas desfechos comportamentais (14 estudos, n = 461), observou-se efeito moderado (g = 0,37). Os desfechos cognitivos isoladamente (39 ensaios, n = 2.896) mostraram efeito grande (g = 0,60), porém com elevada heterogeneidade (I² = 88,1%) e certeza muito baixa. Conclui-se que a EMTr de alta frequência aplicada sobre o córtex pré-frontal dorsolateral (esquerdo ou bilateral) mostra-se eficaz para sintomas cognitivos e comportamentais na DA, sobretudo quando administrada em protocolos de múltiplas sessões, com intensidades entre 80–110% do limiar motor, ao longo de 4 a 6 semanas, o que tem se associado a ganhos clínicos mais consistentes e duradouros. Apesar dos resultados promissores, especialmente nos desfechos cognitivos, são necessários ensaios clínicos padronizados e revisões de alta qualidade para fortalecer a evidência e possibilitar a generalização para outros subtipos de demência, orientando recomendações clínicas mais amplas.

- Abstract  
  Neurodegenerative diseases in the elderly represent a growing global health problem, with Alzheimer’s disease (AD) being the leading cause. Repetitive transcranial magnetic stimulation (rTMS) has emerged as a promising non-pharmacological intervention for cognitive and behavioral symptoms. This umbrella review of meta-analyses evaluated the efficacy of rTMS in neurodegenerative dementias. The study followed PRISMA guidelines and was registered in PROSPERO (CRD42023489100). A systematic search was conducted in PubMed/MEDLINE, Embase, SciELO, Web of Science, and Cochrane CENTRAL. Two reviewers independently performed study selection, data extraction, methodological quality assessment, and risk of bias evaluation. The AMSTAR-2 and ROBIS tools assessed methodological quality and risk of bias, respectively, while the GRADE approach verified certainty of evidence. A meta-umbrella synthesis was conducted using R software. From 2,288 records identified, 16 review articles containing 33 meta-analytic graphs encompassing 57 randomized clinical trials on AD were included. In the population assessed for combined cognitive and behavioral outcomes (16 studies, n = 350), rTMS showed a small but significant effect (g = 0.40; 95% CI: 0.19–0.60; I² = 42.9%), with moderate certainty. For behavioral outcomes alone (14 studies, n = 461), a moderate effect was observed (g = 0.37). Cognitive outcomes (39 trials, n = 2,896) showed a large effect (g = 0.60), but with high heterogeneity (I² = 88.1%) and very low certainty. It is concluded that high-frequency rTMS applied over the dorsolateral prefrontal cortex (left or bilateral) appears effective for cognitive and behavioral symptoms in AD, especially when administered in multi-session protocols at intensities of 80–110% of motor threshold over 4 to 6 weeks, which have been associated with more consistent and durable clinical gains. Despite promising results, particularly for cognitive outcomes, standardized clinical trials and high-quality reviews are needed to strengthen the evidence and allow generalization to other dementia subtypes, guiding broader clinical recommendations.

## Estrutura das pastas e materiais complementares

1. `1- Tabela geral de extração/`  
   Contém `1- TabelaGeral.xlsx`, tabela geral com todas as informações básicas das metanálises incluídas na revisão.

2. `2- Tabela estudos eleitos (PRISMA)/`  
   Inclui a planilha `2 - V2 -TabelaElegibleStudies.xlsx`, com estudos incluídos e excluídos, e a figura `PRISMA.jpg` com o fluxograma PRISMA da busca e seleção dos estudos.

3. `3- Tabela com intervenção e escalas de desfecho/`  
   Contém `3 - V2 - TabelaIntervention.xlsx`, com parâmetros de intervenção (por exemplo, protocolo de EMTr) e as escalas de desfecho avaliadas nas metanálises.

4. `4- ECR x Metanalise (heat map)/`  
   Reúne a matriz de cruzamento entre ensaios clínicos randomizados (ECRs) e metanálises (`Cruzamento-ECRs_x_Metanalises.xlsx`) e os arquivos de saída da visualização em heat map (`ECRxMETANALISE-grafico.png`, `ECRxMETANALISE-matriz.png`).  
   A subpasta `Python_code_to_convert_table_into_graphic/` contém o notebook `Heatmap_para_METAUMBRELA.ipynb`, utilizado para converter a tabela em gráfico (heat map) em Python.

5. `5- Informações da população/`  
   Contém `5- V2 - TabelaPopulation.xlsx`, com informações sociodemográficas e clínicas das populações incluídas nos ECRs e metanálises.

6. `6- StudiesData (dados estatisticos das metanalises)/`  
   Contém `6- V2 - TabelaStudiesData.xlsx`, com dados estatísticos das metanálises (por exemplo, tamanhos de efeito, intervalos de confiança, heterogeneidade).

7. `7- Tabela com robis formatado/`  
   Inclui `7- ROBIS FORMATADO.xlsx`, com a avaliação do risco de viés das revisões sistemáticas por meio da ferramenta ROBIS.

8. `8- Metaumbrella (dados estatisticos dos ECR)/`  
   Reúne `8- v2 - Metaumbrella.xlsx`, com os dados de cada ECR por metanálise utilizados na síntese tipo meta-umbrella. A subpasta `Exemplo de Banco de dados para o R Studio/` contém um exemplo de banco de dados (`df.radua2019.xlsx`, entre outros arquivos de apoio) e anotações de colunas para uso no R. Por último, a subpasta `Exemplo de codigo RStudio/` contém um documento com exemplo de código em R para rodar as análises.

9. `9- Tabela AMSTAR e GRADE resumido por estudo/`  
   Contém `9- AMSTAR per metanalyses.xlsx`, com os resultados da avaliação metodológica por meio do AMSTAR-2 e a síntese GRADE resumida por estudo de metanálise.

10. `10- GRADE por metanalise/`  
    Inclui `GRADE-PRO.mhtml`, arquivo exportado do GRADEpro com o GRADE de cada metanálise.

11. `11- Search results/`  
    Inclui os resultados das buscas exportados das bases de dados analisadas (MEDLINE/PubMed, Cochrane, Sciedo, Embase e Web of Science).

   
## Uso dos dados

Os arquivos são disponibilizados para fins de transparência, reprodutibilidade e aprofundamento metodológico. Recomenda-se que qualquer reutilização dos dados, figuras ou códigos cite adequadamente a dissertação original e este repositório.

### Como citar

CARPINTEIRO II, Antonio Sérgio Costa. *Uma revisão guarda-chuva de metanálises avaliando a eficácia da estimulação magnética transcraniana em demências*. Dissertação (Mestrado em Psiquiatria) – Instituto de Psiquiatria (IPUB), Universidade Federal do Rio de Janeiro, Rio de Janeiro, 2025.

