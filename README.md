# A GAN Based method for Cross-Scene Classification of Hyperspectral Scenes Captured by Different Sensors
The code in this repository implements the method proposed in our paper, which is currently being submitted for peer review.<br>
The codes are written in Python in the Jupyter Notebook environment using Google Colab.<br>
This research utilizes two datasets: RPaviaU-DPaviaC and EHangzhou-RPaviaHR. Details on these datasets can be found in our paper.<br>
<br>
<strong>HyperSpectral Datasets:</strong><br>
The hyperspectral datasets used in our research were provided to us by <a href="https://scholar.google.com/citations?user=sAnqbRwAAAAJ" target="_blank">Dr. Minchao Ye</a>.
Since we received the datasets via email and access to a private repository, we may not have the permission to redistribute it in a public repository.
Hence, the hyperspectral sences are not included with the codes in this repository.<br>
To reproduce the results presented here, please obtain the following .mat data files and add them to a folder named GANHDA in your Google Drive:<br>
* DataCube-RPaviaU-DPaviaC.mat
* DataCube-EHangzhou-RPaviaHR.mat
<br>
<strong>Code Structure:</strong><br>
There are two notebook files provided, each for a dataset. A pretrained weight is also provided for each database.<br>
Each notebook is comprised of three sections named: Initialization, Tranining and Evaluation.<br>
in order to run the code with pretrained weights, please simply skip the training sections and run the othe two sections.
<br>
<br>
<strong>Import to Cloab:</strong><br>
Please use the following links to quickly import the notebookes into Google Colab:<br>
RPaviaU-DPaviaC:https://colab.research.google.com/github/amirmah/HSI_GANHDA/blob/main/1-RPaviaU_DPaviaC.ipynb<br>
EHangzhou-RPaviaHR:https://colab.research.google.com/github/amirmah/HSI_GANHDA/blob/main/2-EHangzou_RPaviaHR.ipynb
