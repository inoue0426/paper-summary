# Deep learning for drug repurposing: Methods, databases, and applications

Pan et al, 2022, WIREs computational molecular science


1. What kind of research(abstract)?

This is the review paper about how to use deep learning for drug repurposing.
This paper introduces:
- databases
- SOTA DL methods
- application to deal with COVID-19

2. What is progress from previous research?

N/A

3. What is the specific topic?

Introducing how to use DNN for drug repurposing.

- Source:
    - Databases
        - compounds
        - proteins
        - disease knowledge

Should read the table 1 to check all databases.

- Representation:
    - Feature Vectors
        - Graphs
            - Molcular 2D structure
                - mol2vec: https://github.com/samoturk/mol2vec
                - RDKit: https://github.com/rdkit/rdkit
            - 3D
                - ProtVec: https://arxiv.org/abs/1503.05140
        - Sequences
            - SMILES
        - Text

- Models:
    - DNN
        - RNN
        - GNN
            - ProteinGCN: https://github.com/malllabiisc/ProteinGCN
        - VAE

Should read the table 2 to check all models.

- Tasks:
    - DTA
    - drug–target interaction (DTI) and compound–protein interaction (CPI)
        - MCPINN: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6617572/
        - TransformerCPI: https://github.com/lifanchen-simm/transformerCPI
        - NeoDTI: https://github.com/FangpingWan/NeoDTI
    - Drug Disease Association

Should read the Figure 5 to check applications.

4. How did the method evaluate its usefulness?

NA

5. Are there any discussions?

Consequently, the most important thing in computational biology is data quality. In addtion, expert annotation is expensive and slow. So, automatic annotating and data augmentation is significant.

Transfer learning, semi-supervised few-shot learning and precision medicine drug repurposing are trending.


6. What is the next article you should read?

NA
