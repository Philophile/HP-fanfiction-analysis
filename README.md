# HP fanfiction analysis
This project aims at analysing the stories published in the Harry Potter section of fanfiction.net (https://www.fanfiction.net/book/Harry-Potter/).
The key objective is to create a recommandation algorithm which would identify the similarities in the stories in terms of narrative structures and tropes, independently of the characters in the story.

This project will be structured in four main steps :

I- Preliminary Analysis based on the summary and metadata of all stories

II- First categorisation of the stories, based on the summary

III- Scraping of the stories on a restricted corpus and constitution of a Database

IV- Analysis of the relation between the characters 

V- Construction of a first recommandation algorithm

VI- Analysis of the evolution of the relations between the characters

VII- Constitution of the final recommandation based on evolution of the story

## I- Preliminary Analysis

The first analysis is based on the public dataset available here : https://github.com/nt03/HarryPotter_fanfics/tree/master/ffnet, or in Kaggle Dataset : https://www.kaggle.com/datasets/nehatiwari03/harry-potter-fanfiction-data

The notebook for this analysis is first available here : https://www.kaggle.com/code/philophile/fanfiction-analysis-by-language

This Notebook aims at making a first analysis of the data of the Fanfiction Harry Potter, on the summary of the fanfictions before starting a deeper exploration of the content of the fanfiction themselves.

In particular, a first goal would be to identify specifities of the different stories between languages, in terms of length, characters, etc.

A second objective will be to identify the main factors which determines if a story is finished or not. A first approximation, the length would be a major factor (a short story will be more easily finished than a long novel-like adventure), but we may identify (or not) other relevant factors.


## II- First categorisation

I will conduct a first categorisation of the stories based on the summary written by the author. This categorisation aims at finding similarities between the stories based on the identified tropes in the HP fanfiction world (8th year at Hogwarts, Mariage Law, Veela/Vampire/Werewolf mate, etc) in addition to current categorisation by characters or genre.
We will focus at first on the English corpus for this task. Later on, we will reapply the work on the French corpus and then other languages.

This categorisation is inspired by some of the code presented in  *Blueprints for Text Analysis using Python*, Jens Albrecht, Sidharth Ramachandran, Christian Winkler, O'Reilly, 2020. Their whole code can be found here and has been a great inspiration and help for this project : https://github.com/blueprints-for-text-analytics-python/blueprints-text

## III- Scraping & Database

## IV- Analysis of Relations

## V- Recommandation algorithm

## VI- Evolutions of Relations

## VII- Recommandation based on evolution of the relations
