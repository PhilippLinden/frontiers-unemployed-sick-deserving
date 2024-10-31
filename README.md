# Unemployed + Sick = More Deserving? A Survey Experiment on How the Medicalization of Unemployment Affects Public Opinion

## Abstract

The literature on the social legitimacy of welfare benefits has shown that sick persons are perceived more deserving than unemployed individuals. However, these studies examine sick and unemployed persons as distinct groups, while unemployment and sickness are in fact strongly related. Policymakers across Europe have been increasingly concerned with discouraging a medicalization of unemployment and activating sick unemployed persons. Therefore, it is crucial to understand welfare attitudes toward this group. Using a factorial survey fielded with a representative sample of German-speaking adults (N=2,621), we investigate how sickness affects attitudes toward a hypothetical unemployed person on three dimensions: benefit levels, conditions, and sanctions. Respondents allocated similar benefit levels to unemployed persons regardless of whether they have an illness. Yet, they were more hesitant to apply existing conditions (e.g., active job search, job training) or sanction benefits when the unemployed person was also sick. This is except for conditions that tie benefits to obligatory health services (back training or psychological counseling) which was supported by the majority of respondents. Our research shows that the German public is not more generous and only partially more lenient toward sick unemployed persons as there is strong support for conditions targeted at overcoming ill health for this group. The findings underscore that sickness matters for how unemployed persons are perceived, but the impact varies across different dimensions of welfare attitudes.

----

The paper by Linden, P. & Reibling, N. with the DOI: 10.3389/fsoc.2022.738397 can be obtained [here](https://www.frontiersin.org/articles/10.3389/fsoc.2022.738397/full). If you have any questions, please send an E-Mail to [Linden Research](mailto:research@linden-online.com).

----

### History

`2023-05-01`
:  Setup

---

### Directories

`\01src`
:  Source materials, raw data

`\02prc`
:  Processed data and analytical scripts (in subfolders)

`\03doc`
:  Documentation and output incl. figures and tables

`\04pap`
:  References for obtaining the paper

---

### Description

This repository contains the code for the analysis in the paper entitled "Unemployed + Sick = More Deserving? A Survey Experiment on How the Medicalization of Unemployment Affects Public Opinion" which is published under open access in [Frontiers in Sociology](https://www.frontiersin.org/articles/10.3389/fsoc.2022.738397/full).

The data for this analysis comes from a self-designed and self-programmed factorial survey with vignettes. Vignette are little case descriptions of situations or individuals, which allow to systematically vary factors under study (e.g. gender, age etc.). The factorial survey was implemented in the [YouGov panel Germany](https://yougov.de/panel/) with roughly 350.000 panelists. From here, we were able to recruit a sample of N=2.621 individuals, which are representative on the key variables gender, age, education and residence at state level. The raw data set is available after registration [here](https://search.gesis.org/research_data/SDN-10.7802-2465?doi=10.7802/2465).

---

### Replication instruction

All analysis were done in Stata 16 and under Windows 11. Please follow the steps listed below to reproduce findings:

1. Fork the repository / Sync fork if necessary
2. Get the data at [GESIS Datenarchiv](https://search.gesis.org/research_data/SDN-10.7802-2465?doi=10.7802/2465). You only need to register once.
2. Open and read the file `master.do` in Stata from the directory `input`
    - In this file, adapt the global wdir as specified
3. Run the file `master.do` in the `input` folder
4. See the output directories `\03doc\fig`, `03doc\tab` & `03doc\var` for output
