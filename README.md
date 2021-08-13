# Project: big tech lobby

This is a project for Lede week 10. 

Through web scraping of [US Senate lobbying disclosure](https://lda.senate.gov/filings/public/filing/search/), I analyzed lobbying trend of tech giants.
The link to the story is [here](https://hiromisa.github.io/final_project/).

---
## Data
All data I used for analysis is coming from [US Senate lobbying disclosure](https://lda.senate.gov/filings/public/filing/search/).
I picked 5 big technology companies (Amazon, Applle, Facebook, Google, Microsoft) as 'Registrant'. Some subsidiary is not included.

Though Original dataset contains the data before 2010, I mainly used the data between 2011-2021(2Q).  
  
---
## Methodology
5 notebook shows every step I took.

[BigTech_lobbying_1](https://github.com/Hiromisa/project_bigtech_lobby/blob/main/BigTech_lobbying_1_create_table.ipynb) is the notebook for scraping table and url on the website. I kept Amendment in dataframe. With manual check outside jupyternoteebook, formatted the table as [bigtech_lobby - formatted.csv](https://github.com/Hiromisa/project_bigtech_lobby/blob/main/bigtech_lobb%20-%20formatted.csv).

[BigTech_lobbying_2](https://github.com/Hiromisa/project_bigtech_lobby/blob/main/BigTech_lobbying_2_pdf_parse.ipynb) is the notebook for scraping PDFs based on url.

[BigTech_lobbying_3](https://github.com/Hiromisa/project_bigtech_lobby/blob/main/BigTech_lobbying_3_analysis1.ipynb) and [BigTech_lobbying_4](https://github.com/Hiromisa/project_bigtech_lobby/blob/main/BigTech_lobbying_4_analysis2.ipynb) are the notebook for analysis.

[BigTech_lobbying_5](https://github.com/Hiromisa/project_bigtech_lobby/blob/main/BigTech_lobbying_5_analysis_reference.ipynb) is the notebook for references.

