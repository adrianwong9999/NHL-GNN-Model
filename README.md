# NHL-GNN-Model

The code to generate all three models is contained within the jupyter notebook named main.ipynb. The first two cell blocks contain the code to run the simple GNN model.

The complex GNN and ANN models share some of the cell blocks. These cell blocks include the ones defining the data transformer, which is responsible for labelling and encoding the data as well as creating the training, validation and testing data sets. Other such cell blocks contain the trainer functions, which help with the time series based evaluation methods, as well as utility functions needed to calculate RPS. 

The cell blocks needed to run the GNN and ANN models are the ones contain the run_gnn_cont and run_flat_cont functions. After they have been run the following cell block will generate the corresponding confusion matrix.

Copy of Report: https://drive.google.com/file/d/18M5tG_MNOuBVA4MisaEArsEmxQJOd6Jd/view?usp=sharing
