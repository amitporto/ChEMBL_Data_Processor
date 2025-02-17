# ChEMBL_Data_Processor
This tool is designed for processing or curating the large dataset downloaded from ChEMBL and prepare it for classification-based QSAR modeling.

**#Details**
This tool provides Tkinter based GUI to process and curate the .csv data downloaded from ChEMBL based on some user specific criteria.
It includes a column at the end of the processed file as 'Active' that contained binary values (1 or 0) based on the activity cut-off value specified by the user.
It also download a file where the user may check which data-points are duplicates and have large variations in the reported activity values. The user may decide whether to keep these data-points or not.

# Requirements
Anaconda
Rdkit
Anaconda may be downloaded from https://www.anaconda.com/
Install Rdkit latest version from the command pip install rdkit

# Warning
This tool removes some columns from ChEMBL data and reatains only limited numer of columns with following headings: 'Molecule ChEMBL ID','Molecule Name', 'Molecule Max Phase','Molecular Weight', '#RO5 Violations', 'AlogP','Smiles', 'Standard Type', 'Standard Relation','Standard Value', 'Standard Units','Assay ChEMBL ID', 'Assay Description', 'Assay Type', 'BAO Format ID', 'BAO Label', 'Assay Organism', 'Assay Cell Type', 'Target ChEMBL ID','Target Name','Target Organism','Target Type', 'Document ChEMBL ID'
