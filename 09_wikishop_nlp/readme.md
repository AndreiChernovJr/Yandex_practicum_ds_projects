# Comments classification

**Task:**

- Speed up the moderation of comments in the community by automating their toxicity assessment. Train the model to classify comments as positive and negative.

**Description:**

- To launch a new service, an online store needs a tool that will search for toxic comments and send them for moderation. Users can edit and add product descriptions, just like in community wikis. That is, clients suggest their edits and comment on others' changes. The model was trained to classify comments into positive and negative. Analyzed a dataset with markup on the toxicity of edits. A model with F1 metric at 0.78 was built. Texts were vectorized using word2vec, tdidf, Spacy.

**Used Libraries:**

- Pandas, Python, NLTK, LightGBM, Sklearn, Spacy, re 
