## Projects and Research
Here are some of the projects that  i have worked on during my M.Sc 




### 1. Incorporating Active learning Methods with Contextualized Sentence Representations 
Final project in NLP class, Tel Aviv Univesity 2019. Together with Danielle Hausler.
An empirical comparison study on two different sentence representations (SentenceBert and Best-as-Service ) which utilize BERT contextualized word representations. We implement several Active learning methods and compare their performances on different types of text Datasets and tasks. Until submission date (May 2020) There were almost no papers that deals with "Bertology" and Active learning. [Github repository](https://github.com/daniellehausler/nlp_active_learning)  and the (unpublished) [Paper](https://github.com/katzurik/katzurik.github.io/blob/main/NLP_katz_hausler.pdf)

![Image](https://github.com/katzurik/katzurik.github.io/blob/main/images/mr_f1_SenB.png?raw=true)

### 2. Besov smoothness analysis on Deep learning Text classifier With different Word Representation methods
Final project in Mathematical foundations of machine learning class, Tel Aviv Univesity 2019. Together with Danielle Hausler.
We used [this method](https://arxiv.org/abs/1710.03263) to quantify the geometry of the clustering within each layer representation using the Besov index of smoothness.
We have shown that the Besov smoothness increase from layer to layer inside the model architecture. We have compared different word representations (One-hot-encoding and FastText and Word2Vec) and showed that the Besov smoothness indeed increases as a function of the goodness of representation. [Github repository](https://github.com/katzurik/NLP_besov_smoothness) and [Presentation](https://github.com/katzurik/katzurik.github.io/blob/main/function%20space%20analysis%20of%20NLP%20models.pdf)

![Image](https://github.com/katzurik/katzurik.github.io/blob/main/images/besov.jpeg?raw=true)


### 3. Snack2Vec - Snack Ingredient Embedding from product food Labels
Part of the final project in Application in Data Science class, Tel Aviv University 2020. Using the food labels ingredients list of ~ 25K different snacks, I have managed project ingredients of snacks into the "Snack" space. Training a Skip-gram fastText model on the ingredient lists as if they were sentences with sequential context. After assigning a vector for each ingredient I have max/average pool the vectors from each list into a single vector that represents the parent snack. Here is a TSNE plot of snacks from a different category


```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/katzurik/katzurik.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
