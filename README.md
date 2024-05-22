# Unsupervised ECG Classifier
 
Design and implement an ML-based automatic electrocardiogram interpretation algorithm in python. 
The aim is to partition electrocardiogram signals into distinct classes without cardiologist-supplied labels. 
The supplied signal labels are only to be used during testing and evaluation, not during model training.

- use the [PTB-XL dataset available on PhysioNet](https://www.physionet.org/content/ptb-xl/1.0.3/)

### Setup
 
 ```
conda create --name py311-ecgsorter python=3.11
conda activate py311-ecgsorter
````
```
pip install notebook
python -m ipykernel install --user --name=py311-ecgsorter
```
```
cd ~/ecg-sorter
pip install -r requirements.txt
conda deactivate
```

### Start Notebook
```
cd ~/ecg-sorter
jupyter notebook
```
Then double-click to open `main_notebook.ipynb`, select the correct IPython kernel (`py311-ecgsorter`), and run the notebook.
