# Evaluating RNN Models for Multi-Step Traffic Matrix Prediction
The model with entire details will be uploaded soon


# GÉANT Backbone Network Data

The GÉANT Backbone Network dataset is the most well-known Traffic Matrix dataset. You can download the raw data [here](https://totem.info.ucl.ac.be/dataset.html).

GÉANT Backbone Network topology consists of 23 nodes and 38 links, as described below:

<div align="center">
  <img src="geant-topo.png" alt="GÉANT Backbone Network" width="400" />
</div>

The dataset contains Traffic Matrices from 4 months of capturing with a 15-minute interval. Originally, each traffic matrix is stored in a single XML file. For more convenience in using the dataset, we make a script (dataset/geant-dataset-converter.py) to convert all of the separate matrices into a single file. dataset/geant_flat_tms.csv is the final converted dataset. The dataset consists of 10772 traffic matrices.



