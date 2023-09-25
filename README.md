# Vector-Space-Semantics-for-Similarity-between-Eastenders-Characters

In this project, a vector representation of a document containing lines spoken by a character in the Eastenders script data (i.e. from the file training.csv) is created, followed by improving that representation such that each character vector is maximially distinguished from the other character documents. This distinction is measured by how well a simple information retrieval classification method can select documents from validation and test data as belonging to the correct class of document (i.e. deciding which character spoke the lines by measuring the similarity of those character document vectors to those built in training). 

There are two jupyter notebooks which uses WordCount and TF-IDF vectorizer respectively, along with other preprocessing techniques applied. The implementation and results of the project are mentioned in the PDF Report given.
