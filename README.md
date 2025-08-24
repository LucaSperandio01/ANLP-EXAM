# ANLP-EXAM
## Usage
This code is aimed to research how transformer-based models like ProtBert represent single amino acids mutation in proteins, in order to understand if those models can capture just from the amino acid sequence, secondary features that can lead to an early prediction of aspects like protein functionality, stability, ecc.
## Dataset 
The dataset used is https://huggingface.co/datasets/Trelis/protein_stability_single_mutation and containes several data about several unmutated protein sequences and mutated sequences obtained from those original ones.
In order to better visualize the results, the mutation were grouped based on the name of the original protein the were obtained from.
## Model 
As already said in the usage section, the model use for this investigation is ProtBert a pretrained model for amino acid sequence prediction task
## Libraries
The sklearn library was used in order to compute a PCA analysis on the attention masks obtained after tokenization trought the ProtBert tokenizer.
