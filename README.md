ProBASS – a language model with sequence and structural features for predicting the effect of mutations on binding affinity.

Here we introduce a model (Probass) which is fine-tuned, incorporating features derived from both Protein Language models ESM-2 and ESM-IF1.

This model is designed for the prediction of ddGbind values, which serve as indicators of both the sequence and structural attributes of the mutated protein complexes.

The model is an efficient way to predict the effect of mutations on protein binding affinity. 

More details regarding the Protein Language models can be accessible from here: https://github.com/facebookresearch/esm.

The following notebooks can be used to explore the basic functionality of Probass.

To extract embeddings protocols are available here: https://github.com/facebookresearch/esm.

The installation of the following packages is necessary for proper operation. 


Install necessary packages.

conda install pytorch cudatoolkit=11.3 -c pytorch
conda install pyg -c pyg -c conda-forge
conda install pip
pip install biotite
pip install git+https://github.com/facebookresearch/esm.git

