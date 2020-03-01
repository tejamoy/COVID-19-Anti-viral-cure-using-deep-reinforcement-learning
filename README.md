# COVID-19-Anti-viral-cure-using-deep-reinforcement-learning
This is a research that attempts to use deep reinforecement learning to find an anti-viral cure for the corona virus. It is a research done based on the efforts of M. Benhenda, “ChemGAN challenge for drug discovery: can AI reproduce natural chemical diversity?,” 2017 and https://github.com/mostafachatillon/ChemGAN-challenge

# Dataset
The "dataset_cleansed.smi" found in the "Dataset" folder was gotten from  “GitHub - topazape/LSTM_Chem: Implementation of the paper - Generative Recurrent Networks for De Novo Drug Design.”

# Training the dataset
The "ORGANIC.py" is found in the "Deep learning model" folder, this is used to run the "dataset_cleansed.smi" file.

# Results
- The COVID-19 REPORTs.pdf is a detailed documentation of the research.
- The "BINDINGAFFINITES.csv" found in the "COVID-19 Binding" folder shows the binding affinites of all the good sample molecules or SMILES
- The "Good sample SMILES.txt" found in the "COVID-19 Binding" folder shows the 10 good sample SMILES generated by the Deep reinforcement learning model
- The "Covid-19.pdb" found in the "COVID-19 Binding" folder shows in the corona virus structure 
- The "Viewbindingaffinity.pse" found in the "COVID-19 Binding" folder shows the candidate molecule bound to the virus.

# requirement
Updated versions of;

- tensorflow
- future
- editdistance
- PyMOL - Used to bind the virus to the 10 good sample molecules
- PyRX - Used to view structures of the virus e.g "Covid-19.pdb" or "Viewbindingaffinity.pse" files

# Note
To change the dataset to whatever dataset you choose;
- Delete the "checkpoints" folder from the "Deep learning model" folder
- Change the trainfile ("../Dataset/dataset_cleansed.smi") from the "exp.json" file to the dataset you download ("../Dataset/****.smi")

