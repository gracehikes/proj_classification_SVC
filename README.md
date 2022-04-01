
# Abstract
Support Vector Machines (SVM) and Supported Vector Clustering (SVC) are some of the frequently used tools for the purposes of classification. Both are very powerful tools, with applications in both image and text classification. Text analyses on what people write in their dating profile self-summaries may help uncover similarities or differences for features like gender, age group, socio-economic status, etc.


# Methodology
My analysis scope:
* apply Google's Universal Sentence Encoder and get 512 embedding dimensions for each essay
* apply SVC algorithm on the embedding dimensions of essays, along with dating app user's gender and age group
* review heat map and classification accuracy scores for gender and age group


# Results
The classification heat maps and accuracy metrics indicated that the embeddings were somewhat predictive of the gender of the dating app user who wrote the essay. Gender prediction accuracy of 65%. Similar explorations by age group did not show classifications of good accuracies other than for those in their 20s.

<p align="center">
  <img src="https://github.com/gracehikes/proj_dating_essays_tSNE_clusters/blob/main/images/tSNE%20visual%20cluster%20by%20gender.png" width=95%>
</p>


# More Details
Full report found [here](https://github.com/gracehikes/proj_dating_essays_tSNE_clusters/blob/main/graceyang_final_thesis_filed.pdf).
