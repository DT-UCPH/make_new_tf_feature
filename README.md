# Make new Text Fabric feature

If you run the code in the notebook, a new feature lemma_bare will be added automatically to your local SBLGNT dataset, which you can find [here](https://github.com/centerblc/sblgnt).
The feature lemma in this dataset contains Greek lemma's of the words in the New Testament, but they have accents and are sometimes capitalized, which makes it less easy to search for them. This feature is the basis for the new feature lemma_bare. From the original lemma, the accents are stripped, and the letters are converted to lower case. 
