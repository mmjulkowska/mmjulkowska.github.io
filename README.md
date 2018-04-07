## Halloski! 

Welcome to my personal website - I am Magda and I work as a Postdoctoral Fellow in the [group of Prof. Mark Tester](http://saltyworld.org) in [KAUST](http://kaust.edu.sa), Saudi Arabia. In my research I focus on how salt stress affects plant architecture (especially the underground bit of the plant). 

## My bio:

I was born in [Zyrardow](https://en.wikipedia.org/wiki/%C5%BByrard%C3%B3w), a small industrial city in Poland build with red-bricks. My parents moved to the Netherlands, where I finished my high-school and started my intellectual germination at the University of Amsterdam. I got my BSc degree in General Biology and MSc degree in Green Life Science. During my MSc degree I did two fun MSc projects, one in Amsterdam, focusing on [SnRK2.4/2.10 interaction with phospholipids](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3533798/) and the other one in Canberra, on [blue-light induced processes leading to germination of wheat](https://www.ncbi.nlm.nih.gov/pubmed/23588419).

Later, my seedling brain was nurtured by Prof. Christa Testerink, during my PhD project. I studied Root System Architecture of Arabidopsis HapMap population, developed a simple Root-Fit model to describe stress-induced reprogramming of the architecture, and explored the salt stress induced changes in the rosette size. During my PhD I also studied on protein-lipid interactions using [liposome binding assays](https://link.springer.com/protocol/10.1007%2F978-1-62703-401-2_24) focusing on the interactions between [Phosphatidic Acid and Arabidopsis SnRK2.4/2.10 proteins](https://onlinelibrary.wiley.com/doi/abs/10.1111/pce.12421). 

Additionally, together with (back then) BSc. student Elmer Swart we collected some Arabidopsis accessions throughout the Netherlands, to examine their salinity tolerance.

![screenshot 2018-04-07 22 09 28](https://user-images.githubusercontent.com/14832460/38459292-94ece320-3ab0-11e8-9972-59b0c7ad0e3d.png)
![magdalena-julkowska-sils-uva](https://user-images.githubusercontent.com/14832460/38459344-14f67284-3ab1-11e8-998f-6c071f672c8e.jpeg)

Right now I am having a post-doc fun in KAUST Saudi Arabia. I am focusing on (1) salt-induced changes in root-to-shoot ratio in Arabidopsis, (2) study the expression patterns in plants with enhanced sodium accumulation in their roots and (3) developing tools for data analysis based on R/Shiny. I am passionate about capturing plant architecture using simple models, understanding plant physiology and salinity tolerance. I love coding in R, BIG data analysis and sharing whatever I know with whomever cares to listen. 

Occasionally, I join for fieldwork - either looking for native Saudi Arabidopsis, or digging out the tomatoes from the field trials to look at their roots.

![img_0473](https://user-images.githubusercontent.com/14832460/38459304-b4e4d390-3ab0-11e8-9cd3-4046e9f3a062.jpg)

I am an [active reviewer](https://publons.com/author/1329791/magdalena-m-julkowska#profile) for plant science journals, a [reviewing editor at Frontiers in Plant Science](https://loop.frontiersin.org/people/345613/overview) and a [Plantae Fellow](https://community.plantae.org/user/mmjulkowska) writting small paper summaries for ["What we're reading"](https://plantae.org/research/wwrtw/) series, which appears weakly on the Plantae website. You can find the bits that I write [here](https://community.plantae.org/user/mmjulkowska/articles). 

![cropped-head-triptic](https://user-images.githubusercontent.com/14832460/38459301-ae5d5e84-3ab0-11e8-80d4-0959563ba1da.jpg)

Working at KAUST gives me a unique opportunity to experience culture and landscape that is very different from my own. You can read about my experiences of the Middle East on [my blog](https://mmjulkowska.wordpress.com/). 


## More background on my research:

Salt stress induces quiescence of growth through modification of cell cycle activity, cell expansion and cell wall extensibility. The period of initial growth arrest and the extent of recovered growth differs between individual organs leading to altered plant morphology. So far we studied altered morphology of Root System Architecture, by capturing growth dynamics in simple descriptive models. By examining natural variation therein we identified four distinct responses, which corresponded to maintenance of ion equilibrium in shoot tissue. When Root System Architecture data was used for Genome Wide Association Studies, we were able to identify a number of novel candidate genes as well as genes previously linked to salinity tolerance, for which we unravelled their role in root development. Our results show how study of growth dynamics lead to novel plant trait discovery, which is especially relevant in these times of fast development in plant phenotyping approaches.


# Projects

```
## MVApp
```
![screenshot 2018-04-05 14 35 59](https://user-images.githubusercontent.com/14832460/38459524-66951058-3ab3-11e8-9d08-52b755601277.png)

Plants are master shape-shifters, constantly adapting their architecture to enhance resource acquisition, ensuring reproductive success. These metamorphoses are governed by genotype and environment (GxE) interactions. Understanding the full range of plant’s morphological versatility, environmental triggers and adaptive relevance often requires a thorough assessment of large numbers of genotypes under various conditions. Recent advances in phenotyping technologies allow the high-throughput quantification of traits reflecting plant size, shape, photosynthetic efficiency and transpiration rate. With increasing number of phenotypes it is becoming increasingly crucial, and proportionally complicated, to identify redundancy, correlations, and impact in phenotypic datasets. 

To adress all of the above, together with a group of five talented PhD students at KAUST, we developed the MVApp [MVApp](http://mvapp.kaust.edu.sa/MVApp/), a user-friendly multivariate analysis tool for large or small datasets.

The MVApp features include:
1.	Curve fitting for plant growth estimation
2.	Data curation for possible outlier values
3.	Data examination for significant differences between genotypes or treatments
4.	Correlation analysis across different traits
5.	Principle Component Analysis and Multidimensional Scaling
6.	Clustering analysis (Hierarchical and K-means)
7.  Broad sense heritability estimation
8.  Quantile regression analysis

We hope that the MVApp will be applicable beyond plant science field, contributing to transparent data curation, analysis, and processing, but also serve as a teaching tool for statistical methods for the ones not (yet) familiar with R and Multivariate analysis. 

You can find instructions on how to use it [here](https://mmjulkowska.github.io/MVApp/), and if you dont feel like reading we made some YouTube tutorials available [here](https://www.youtube.com/channel/UCeTCqj3dHWbjIbt9cXVjHMQ).


```
## Salt induced changes in RSA
```
![tpc fig2](https://user-images.githubusercontent.com/14832460/38459700-e5c49a04-3ab5-11e8-8de1-ac509a66ef92.jpg)

While everyone knows that salt stress reduces root growth, salt stress induced changes in Root System Architecture are less studied. During my PhD, I examined natural variation in salt stress by studying the root architectures of 347 Arabidopsis accessions. It was a lot of work! We collected 17 RSA traits in three different conditions, and used this data for Genome Wide Association Study (GWAS). Our GWAS identified 100 loci, among which CYP79B2 and HKT1. CYP79B2 was validated to be involved in maintenance of lateral root growth during salt stress, possibly by altering auxin biosynthesis. Enhanced HKT1 expression in root stelle repressed lateral root formation under salt stress conditions, revealing that while retention of salt ions in the root is an excellent mechanism of salinity tolerance in larger plants, it is detrimental for primordia development in young seedlings. The validation of other identified loci remains to be revealed.

The data was integrated into an on-line app, where you can have fun comparing the collected phenotypes of individual accessions, correlating different traits and even doing some clustering analysis based on YOUR favourite traits. The app is available [here](http://genseq-h0.science.uva.nl/shiny/App/Salt_NV_Root/) or [here](https://mmjulkowska.shinyapps.io/Salt_NV_RootApp/), while the instructions on how to use it are available [here](https://mmjulkowska.github.io/Salt_NV_RootApp/).

The paper was published as [Julkowska et al., The Plant Cell 2017. DOI: https://doi.org/10.1105/tpc.16.00680](http://www.plantcell.org/content/29/12/3198.long)


```
## Natural variation in rosette size
```


Natural variation among Arabidopsis accessions is broadly recognized as an important genetic resource for identification of mechanisms underlying plant development and stress tolerance. To evaluate the natural variation insalinity stress tolerance, two large-scale experiments were performed on two populations consisting of 160 Arabidopsis accessions each. Traits such as projected rosette area, fresh and dry weight were collected as an estimate for salinity tolerance. The results revealed considerable natural variation in salt stress responses among the accessions studied. The rosette size at salt stress was observed to correspond to the developmental differences observed between the accessions studied at control conditions. Subsequent Genome Wide Association Study (GWAS) revealed associations with novel candidate genes for salinity tolerance such as LRR-KISS, flowering locus KH-domain containing protein and DUF1639 containing protein. The allelic variation underlying LRR-KISS expression is hypothesized to contribute to salinity tolerance by maintaining the rosette growth.

This project was a part of the Ecogenomics course for 3rd year Biology students at University of Amsterdam. The data collection was a real group effort, and I will always be very very thankful for the input and the enthousiasm of those amazing students that I had honour and pleasure to supervise! 

The paper was published as [Julkowska et al., The Journal of Experimental Botany 1060, 67 (8), 2127-2138](https://academic.oup.com/jxb/article/67/8/2127/2885024)


```
## Root-Fit
```

[Root-Fit model](http://www.plantphysiol.org/content/166/3/1387.long)

