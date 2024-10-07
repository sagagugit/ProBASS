[Open in Colab](https://colab.research.google.com/github/sagagugit/ProBASS/blob/main/ProBASS.ipynb)
 
ProBASS – a language model with sequence and structural features for predicting the effect of mutations on binding affinity.

Here we introduce a model (ProBASS) which is fine-tuned, incorporating features derived from both Protein Language models ESM-2 and ESM-IF1.

This model is designed for the prediction of ddGbind values, which serve as indicators of both the sequence and structural attributes of the mutated protein complexes.

The model is an efficient way to predict the effect of mutations on protein binding affinity. 

![pb](https://github.com/sagagugit/ProBASS/assets/122979609/d0a3bd61-ed5a-4a8a-83ff-0ab194a807b7)


More details regarding the Protein Language models can be accessible from here: https://github.com/facebookresearch/esm.


To extract embeddings protocols are available here: https://github.com/facebookresearch/esm.

The installation of the following packages is necessary for proper operation. 


Install necessary packages.

conda install pytorch cudatoolkit=11.3 -c pytorch

conda install pyg -c pyg -c conda-forge

conda install pip

pip install biotite

pip install git+https://github.com/facebookresearch/esm.git

