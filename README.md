# AralSeaProject Literature Review

## Introduction
This is a preliminary literature review for my PhD proposal on small-scale farming in the Aral Sea Basin. I conducted this review on Scopus. This document intends to explain both the methodology followed in developing the literature review and the preliminary results. This review should be intended as a **scoping review** of the field (Munn et al.2018, Lockwood et al. 2019.

## Methodology. 

A scoping review, as the name suggests, is intended to identify the types of evidence available in a certain field, clarify key concepts, and identify knowledge gaps (Munn et al. 2018 p.2). In this case, I deemed the scoping reviewed as adequate to survey the fields of **farming in the Aral Sea Basin (ASB)**  and the **institutional framework** underpinning both the water management and the environmental reparation in the area. Broadly, the guiding **research questions** that guided my research (Lockwood et al. 2019) were:

- What are the key problems regarding farming in ASB?
- What is the structure of the legal/institutional framework in the ASB?

As mentioned, I conducted this review on Scopus, with the following queries: 

- Regarding Farming: Farm OR Farming + "Aral Sea, in title abstracts, and keywords of papers, book chapters, and conference papers labeled in Scopus under the tag "social sciences". Later on, I searched for "Agriculture" + "Aral Sea" with the same limitations. I exported the results in .csv format and I then combined the two datasets in Rstudio using the rbind function.

- Regarding the legal institutional framework: I searched on Scopus for the terms "Aral Sea" + "Law" OR "Legal", limiting the results to English Language.

I then analyzed the data using the bibliometrix package in Rstudio (Aria and Cuccurullo 2017) to obtain a comprehensive map of the field. Following is a brief summary of the data analysis. 

- I converted the into two bibliometrix data frames which I named "AgriData" and "LegData"
- I then performed descriptive analysis on both data sets using, firstly the "biblioanalysis" function of the packaged and then the "summary function", which is able to yield a comprehensive analysis of the surveyed field under various parameters (most cited authors, most cited papers, etc.). The obtained datasets are available within the Rproj of this literature.

## Results

This section discusses briefly  the differences between the two fields, building on the the summarized datasets named "SmLegData" and "SmAgr".

The two datasets differs in time span, considerign that the Agriculture/Farming center one (from now on "AGR), spans from 1961 2023, while the first article in the legal dataset (LEG), dates 1996. However,in the LEG field, the scientificy production is steadily increasing, with an anual growth rate of 4.68%.

I found particulary interesting the comparisong between the author's keyword choices of the two datasets, which provides insights on the key points of the respective fields. Besides the obvious geographical similarities between the two, reflected by keywords such as "Aral Sea" and "Central Asia", it intesting that both datasets, despite the fairly dinstinctive of water security and management, with the keyword "irrigation", being among the most cited in both datasets. The AGR datasets enphatizes the growning importnace of "climate change", among it keyword, toghether with the "adaptation" theme. On the same line, the LEG dataset is focused on the major related to the enviromental problem such as "regional cooperation" and "enviromental safety". 

## Conclusions

Many more analysis can be performed with these two datasets. Indeed, in-depth analysis of the AGR dataset reveals a prevalence  of quantitative studies, while the LEG dataset is mostly populated by doctrinal-instutitional analysis of the current legal framework, with little empirical information.
















