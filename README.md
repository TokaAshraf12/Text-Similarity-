# Text-Similarity
## This tool constructs a graph given text in a natural language as input, such that a node represents a sentence, and an edge exists from one sentence (node) to another if text similarity between the two is above a user-defined threshold.
- The user should enter the text sentences separated with a dot and enter the similarity threshold.
- The sentences will be parsed and entered to be fitted with the extraction text from sklearn library and calculate the cosine similarity to compare it with the threshold and make an edge between the two sentences if the similarity between them is above the threshold.
