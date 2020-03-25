# EGATMDA
**EGATMDA: Ensembling Graph Attention Networks for Human Microbe-Drug Association prediction.**

# Data description
* drugs: ID and names for drugs.
* microbes: ID and names for microbes.
* diseases: ID and names for diseases.
* adj: interaction pairs between drugs and microbes.
* drug_microbe_associations: associations between drugs and microbes.
* drug_disease_associations: associations between drugs and diseases.
* microbe_disease_associations: associations between microbesa and diseases.
* drug_drug_interaction: interactions between drugs.
* microbe_microbe_interaction: interactions between microbes.
* drug_features: pre-processing feature matrix for drugs.
* microbe_features: genome sequence feature matrix for microbes.
* interaction: known adjacent matrix for drugs and microbes.
* net1: known adjacent matrix for drugs and microbes, i.e., interaction.
* net2: vitual adjacent matrix for drugs and microbes obtained from network Net2.
* net3: vitual adjacent matrix for drugs and microbes obtained from network Net3.
* net123: integrated adjacent matrix for drugs and microbes by fusing net1, net1 and net3.

# Run steps
1. To generate training data and test data.
2. Run main.py to train the model and obtain the predicted scores for microbe-drug associations.

# Requirements
* EGATMDA is implemented to work under Python 3.7.
* Tensorflow
* numpy
* scipy
* sklearn
