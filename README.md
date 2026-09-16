# Parts of speech: the Genoese dialect
This is my project from the course of Natural Language Processing (University of Genoa, 2025). 

### Details of the project
The proposal can be divided in two parts. The first part of the project has been done with my colleagues Matteo Ferrari and Fabrizio Sardo: 
since we had the same idea of working with the Genoese dialect, we have created a small dataset of our dialect, eventually with translation in Italian. 
The second part of the proposal is the core of the project. Since there is not a PoS-tagger tool for the Genoese dialect, we can look for tools for similar languages. 
In particular, Genoese is a dialect in Italy, so Italian is the first language we can consider similar. Since Genoese is spoken in Liguria, which is also neighbouring France, we may have French influences: 
French is the second considered language. For the third language, we have to look further. In terms of phonology, Genoese seems really similar to Portuguese: in this project we can look if this resemblance is present 
even in the parts of speech. The project will consists in the usage of PoS-taggers for Italian, French, and Portuguese for Genoese sentences. 
There will be then an evaluation of the results with a ground truth manually defined.

### Structure of the repository

Folders
- `csv`: `.csv` files obtained from the PoS tagging and then used for evaluation
- `no_titles`: articles from *O Zina* without the titles
- `notebooks`: all the notebooks used to create the final versions of the file, the PoS tagging, and the analysis; `final.ipynb` is the definitive notebook with the pipeline, while the others are the drafts used
- `raw`: articles from *O Zina* 

Files
- `preprocessed.txt`: all the articles from the 8 files in `no_titles`
- `text.txt`: the articles from the first 3 files in `no_titles`, which were the only one used for the project
