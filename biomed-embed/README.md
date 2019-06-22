# Probing Biomedical Embeddings from Language Models


## Pre-trained Models
Please download BioELMo at https://drive.google.com/file/d/1CHRd5YQrt3ys64WfJkJR1KX72-2CaT4I/view?usp=sharing
https://drive.google.com/file/d/19sLZ1NhUtD_bMgTstSRWoVDx6Vm-T8Qt/view?usp=sharing
https://drive.google.com/file/d/15cXEVoRhUQ9oBnHVFP3nx6GQozczgxgP/view?usp=sharing, and save the weights at ```./weights/biomed_elmo_weights.hdf5```, options at ```./weights/biomed_elmo_options.json``` and vocabulary at ```./dict/vocabulary.txt```.

For a general ELMo baseline, save the weights at ```./weights/general_elmo_weights.hdf5``` and options at ```./weights/general_elmo_options.json```.

## Probing Tasks
Probing task for NER on BC2GM is located in ```./ner_probing``` and probing task for NLI on MedNLI is located in ```./nli_probing```. Both directories contain detailed documentations.
