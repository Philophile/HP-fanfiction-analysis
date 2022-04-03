# HP fanfiction analysis
This project aims at analysing the stories published in the Harry Potter section of fanfiction.net (https://www.fanfiction.net/book/Harry-Potter/)
The key objective is to create a recommandation algorithm which would identify the similarities in the stories in terms of narrative structures and tropes, independently of the characters in the story.

This project will be structured in four main steps :

I- Preliminary Analysis based on the summary and metadata of all stories

II- Scraping of the stories on a restricted corpus and constitution of a Database

III- Analysis of the relation between the characters and their evolution in the story

IV- Constitution of the recommandation algorithm

## I- Preliminary Analysis

The first analysis is based on the public dataset available here : https://github.com/nt03/HarryPotter_fanfics/tree/master/ffnet, or in Kaggle Dataset : https://www.kaggle.com/datasets/nehatiwari03/harry-potter-fanfiction-data

The notebook for this analysis is first available here : https://www.kaggle.com/code/philophile/fanfiction-analysis-by-language

This Notebook aims at making a first analysis of the data of the Fanfiction Harry Potter, on the summary of the fanfictions before starting a deeper exploration of the content of the fanfiction themselves.

In particular, a first goal would be to identify specifities of the different stories between languages, in terms of length, characters, etc.

A second objective will be to identify the main factors which determines if a story is finished or not. A first approximation, the length would be a major factor (a short story will be more easily finished than a long novel-like adventure), but we may identify (or not) other relevant factors.



