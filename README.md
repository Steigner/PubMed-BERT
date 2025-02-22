# PubMed-BERT

Project of usage Bidirectional encoder representations from transformers (BERT) on the BBBP dataset. The dataset contains molecules represented using SMILES (textual representation of chemical structures) notation and NAME notation, where each molecule has a binary label: 

* 1 (Penetrant) → penetrates the BBB
* 0 (Non-penetrant) → does not penetrate the BBB.

Depending on this, the PubMedBERT and ChemBERTa transformers were used together with the RoBERTA classifier.

The main idea behind predicting the penetration of chemicals across the blood-brain barrier (BBB) is to determine the ability of a given substance to pass through the BBB and into the brain. This process depends on factors such as molecular size, polarity, lipophilicity and specific interactions with transport mechanisms in the BBB.
