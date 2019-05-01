# Análise Crítica - Visualização de Genes Homólogos Fúngicos do Transcriptoma Pneumocystis Carinii

Neste relatório será realizado uma análise crítica sobre uma visualização presente em um artigo onde é detalhado sobre o Transcriptoma de Pneumocystis carinii durante uma infecção fulminante e o metabolismo dos carboidratos e a compatibilidade com parasitas.

***Artigo:*** [_Transcriptome of Pneumocystis carinii during Fulminate Infection: Carbohydrate Metabolism and the Concept of a Compatible Parasite_](https://www.researchgate.net/publication/215629727_Transcriptome_of_Pneumocystis_carinii_during_Fulminate_Infection_Carbohydrate_Metabolism_and_the_Concept_of_a_Compatible_Parasite).

## Introdução

O ***Pneumocystis carinii*** é um fungo patógeno que é o responsável pela Pneumonia. Para entender todo o processo patológico do ciclo de vida desse fungo, foi realizado durante o artigo o sequenciamento do Transcriptoma e foram anotados 4500 ESTS encontrados durante uma infecção por fulminato.

<img src="https://raw.githubusercontent.com/CatherineTostes/PreviewAnalysis/master/Pneumocystis_carinii.jpg" style="max-width:100%;">

Fonte: https://microbewiki.kenyon.edu/index.php/Pneumocystis_carinii

Para saber quais eram os membros de genes presentes no protozoa Pneumocystis, no processo de sequenciamento o que foi encontrado foi categorizado e anotado para posteriormente ser unificado e realizado a análise do alinhamento para descobrir os genes homólogos.

Com os dados do alinhamento e a comparação dos genes homólogos contra bancos de dados, foram encontrados semelhanças das categorizações genéticas com proteínas de fungos filamentosos, com esses resultados foram feitos gráficos sobre os dados, que serão discutidos abaixo:

## Visualização

Para mostrar a distribuição da proporção com que as proteínas de fungos filamentosos foram encontrados, para representação foi feita um gráfico de pizza fatiada, dividindo os genes, o seu nome e a porcentagem com que foi encontrado dentro do organismo analisado.

Abaixo temos a representação de genes homólogos fúngicos:

<img src="https://raw.githubusercontent.com/CatherineTostes/PreviewAnalysis/master/pizza.png" style="max-width:100%;">
Fonte: Representação gráfica retirada do artigo - https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0000423

## Análise Crítica

O gráfico acima está presente no artigo, e está sendo representado da mesma forma para expor outros resultados, e analisando o gráfico e levando em consideração o ***framework What, Why e How***, devemos os categorizar para entender do que se trata os dados, o que queremos representar, que informações queremos passar e como posso estabelecer a melhor forma para que elas sejam representadas.

<img src="https://raw.githubusercontent.com/CatherineTostes/PreviewAnalysis/master/what-why-how.png" style="max-width:100%;">
- ***What:*** Primeiramente temos que entender o que são os dados, devemos realizar um análise acerca deles, se trata da abstração dos dados.

  Utilizando desse princípio e analisando os dados, temos 13 tipos de homólogos sendo representados e 1 tipo exemplificando outros que não estão anotados. Os genes são: ***Pneumocystis carinii (30%)***, ***Aspergillus spp. (19%)***, ***Neurospora spp. (13%)***, ***Yarrowia lipolytica (8%)***, ***Schizosaccharomyces Pombe (7%)***, ***Cryptococcus spp. (6%)***, ***Candida spp. (4%)***, ***Debaromyces Hansenii (3%)***, ***Other (3%)***, ***Kiuveromyces Lactis (2%)***, ***Magnaporthe Grisea (2%)***, ***Podospora Anserina (1%)***, ***Ashbya Gossypii (1%)***, ***Sacharomyces Cerevisiae (1%)***.

  Esses resultados encontrados mostram a porcentagem dos genes encontrados que eram similares com o protozoa após a infecção por fulminato.

- ***Why:*** Depois de realizar a abstração dos dados, podemos definir o por que iremos os representar, e realizar a abstração das tarefas, definir por que o usuário deve olhar para esses dados.

  Os dados precisam ser representados da melhor forma para que passem as informações corretas, para que o usuário consiga compreender do que se trata os dados, nesse momento devemos avaliar as alternativas de representação.

- ***How:*** Se trata da construção da visualização, como será exibido os dados de forma que a representação visual seja eficaz, respeitando os dados e as tarefas apontadas anteriormente.

Como podemos ver na representação mostrada anteriormente, o gráfico não exprime a ideia certa sobre os dados, a forma correta seria uma visualização onde pudessemos ver a sua proporção (%) de maneira que sua apresentação seja condizente aos números.

Podemos perceber que há uma grande divergência em como as fatias são mostradas e sua porcentagem apresentada, por exemplo, Sacharomyces Cerevisiae (1%) e o Ashbya Gossypii (1%), mas as fatias são visualmente diferentes, como se Ashbya Gossypii, tivesse maior porcentagem do que o Sacharomyces Cerevisiae.

Sugestão de Visualização

Através da análise usando o framework, foi proposta a representação visual abaixo:

<img src="https://raw.githubusercontent.com/CatherineTostes/PreviewAnalysis/master/graph_d3.png" style="max-width:100%;">

## Conclusão

Os dados em sua representação no estilo de divisão de pizza em fatias, apresentava problemas visuais na convergência de sua porcentagem e o tamanho das fatias, os dados foram analisados de acordo com o framework What-Why-How e foi proposta uma nova forma de visualização.
