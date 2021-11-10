# LGBT Legal Change Analysis
## Using Machine Learning to model the relationship between international funding structures and LGBT legal change since 1995

A 2019 analysis [1] suggested that country-level changes to the legal standing of LGBT people over the last 25 years were significantly impacted by the form that each country’s international relationships took.  Velasco’s two way fixed effect model seems to say that the more a country relates to the international community via LGBT focused INGOs (International Non Governmental  Organisation) the more likely that LGBT people’s legal standing improves. Conversely, the model suggests that aid relationships between countries (particularly when said aid makes up a significant proportion of recipient GDP) are sometimes tied to reactive responses against “new” LGBT norms – that is to say, the passing of anti-LGBT legislation. 

Velasco’s dataset [2] records 23 independent variables with annual observations for  110 non-OECD (The Organisation for Economic Co-Operation and Development)  countries covering the dates 1990 – 2016. The model created from it is complex, and perhaps opaque to an audience unfamiliar with statistical methods. My goal was to create transparent predictive models for LGBT legislative change at the country level using only those two independent variables that were easiest to explain: Number of LGBT INGOs and Number of OECD donors.

This problem was modelled both as regression (“how much change was there?”) and as categorisation (“was there any change at all?”). Despite the relative simplicty of my models, I was able to demonstrate the significant relationship between these variables and the possibility of legal change for LGBT people. The two files in this folder are the finalised report, which explains and critiques my methods, and a (messy) Jupyter Notebook containing the code I wrote to produce my analysis. 

[1]	[K. Velasco, ‘A Growing Queer Divide: The Divergence between Transnational Advocacy Networks and Foreign Aid in Diffusing LGBT Policies’, Int. Stud. Q., p. sqz075, Aug. 2019, doi: 10.1093/isq/sqz075.](https://academic.oup.com/isq/article-abstract/64/1/120/5556052?redirectedFrom=fulltext)

[2]	[K. Velasco, ‘Replication Data for: A Growing Queer Divide: The Divergence between Transnational Advocacy Networks and Foreign Aid in Diffusing LGBT Policies’. Mar. 13, 2021. doi: 10.7910/DVN/XINDPB.](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/XINDPB)


