# experiment_evalita_HaSpeeDe

This repository presents an approach to the shared task HaSpeeDe within Evalita 2018. We followed a standard machine learning procedure with training, validation, and testing phases. We considered word embedding as features and deep learning for classification. We tested the effect of merging two datasets in the classification of messages from Facebook and Twitter. We concluded that using data for training and testing from the same social network was a requirement to achieve a good performance. Moreover, adding data from a different social network allowed to improve the results, indicating that more generalized models can be an advantage.

Corresponds to the paper

@article{fortunamerging,
  title={Merging datasets for hate speech classification in Italian},
  author={Fortuna, Paula and Bonavita, Ilaria and Nunes, S{\'e}rgio}
}
