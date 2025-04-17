# Sistemas Inteligentes para a Bioinformática

# Drug-Target Interaction Prediction

Este projeto visa a previsão da interação entre compostos químicos e proteínas alvo (Drug-Target Interaction - DTI), utilizando algoritmos de aprendizagem automática e técnicas de deep learning.

A abordagem proposta permite estimar o grau de ligação entre compostos e proteínas de forma rápida e reduzindo a dependência de métodos laboratoriais dispendiosos.

## Dataset: KIBA

**KIBA** (Kinase Inhibitor BioActivity) — dataset especializado na previsão de interações entre inibidores de quinases e as respetivas proteínas-alvo. Contém informações detalhadas sobre compostos químicos (descritores e SMILES), sequências proteicas e valores de interação binarizados.

## Conteúdo do Repositório

- `main.ipynb` — Notebook principal com todas as etapas do trabalho, da exploração de dados ao treino de modelos.
  
- `KIBA_binarized.csv` — Versão binarizada do dataset KIBA com interações droga-proteína.
  
- `drugs_descriptors_smiles.csv` — Descritores moleculares extraídos a partir de SMILES.
  
- `drugs_morgan_fingerprints.csv` — Impressões digitais de Morgan das drogas.
  
- `protein_descriptors.csv` — Descritores calculados a partir das sequências de proteínas.
  
- `protein_encoding.csv` — Codificação numérica das sequências de aminoácidos.
