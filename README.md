# Representation Learning Impact on Unsupervised Graph Neural Networks via Link Prediction for One-Class Recommendation

- Marcos Gôlo (ICMC/USP) | marcosgolo@usp.br (corresponding author)
- Leonardo Moraes (ICMC/USP) | leonardo.g.moraes@usp.br
- Rudinei Goularte (ICMC/USP) | rudinei@icmc.usp.br
- Ricardo Marcacini (ICMC/USP) | ricardo.marcacini@icmc.usp.br

# Citing:

If you use any part of this code in your research, please cite it using the following BibTex entry
```latex
@article{ref:Golo2023,
  author = {Gôlo, Marcos and Moraes, Leonardo and Goularte, Rudinei and Marcacini, Ricardo},
  title = {Recommender Systems: One-Class Learning and Unsupervised Graph Neural Networks via Link Prediction},
  year = {2023},
  journal = {Journal of Information Data Management},
  publisher={SBC}
}
```

# Abstract
We present a Graph Neural Network (GNN) for One-class Recommendation using link prediction. Traditional recommender systems require positive and negative interactions to recommend items to users, but negative interactions are scarce, making it challenging to cover the scope of non-recommendations. Our proposed approach explores One-Class Learning (OCL) to overcome this limitation by using only one class (positive interactions) to train and predict whether or not a new example belongs to the training class. The paper also proposes an explainability model and performs a qualitative evaluation through the TSNE algorithm in the learned embeddings. The methods' analysis in a two-dimensional projection showed our enriched graph neural network proposal was the only one that could separate the representations of users and items. Moreover, the proposed explainability method showed the user nodes connected with the predicted item are the most important to recommend this item to another user. Other conclusions from the experiments are that Genre and keywords nodes also impact the recommendation.

# Proposal: Unsupervised Graph Neural Networks via Link Prediction for One-Class Recommendation
![Proposal](/images/proposal.jpg)

# Results
![Movies Results](/images/results1.png)
![Recipes Results](/images/results2.png)
![Google Results](/images/results3.png)

# TSNE
![TSNE](/images/TSNE.png)

# Explainability Model
![Exp](/images/epx.png)

# Statistical Test
![Friedman and Nemenyi Post Test](/images/ocr.png)

# File Organization
- Dataset: Dataset files
- Results: total results of each method in each scenario considering all parameters used
- Code: source codes used for the study experiments and result analysis
