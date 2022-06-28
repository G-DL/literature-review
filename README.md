# literature-review

This is based upon the previous, manual download of a dataset from Scopus

Insert the dataset in the same folder as the local version of this repository.

Then run, in order, all cells in this sequence of notebooks:

1) DOAJ_data_collection
2) overlapping_index_and_merging

The folder ./data/ needs to contain the text extracted from the articles that were included in the sample after the last step in (2), aimed at excluding them. We cannot include the actual text, since this is the copy-paste of each individual article not excluded in the previous steps, and we do not hold the copyright. Each article goes into an individual .txt file. We can provide a zip file containing the .txt files that were used in the publication, upon request. Once that is done, run all cells in:

3) LDA
