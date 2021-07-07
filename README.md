# NN-algorithm-comparison-Image-classification-task
In this project, both the multi-layer perceptron (MLP) and the convolutional neural network (CNN) were trained, tested, and optimised on the CIFAR-10 dataset. Libraries used were predominantly PyTorch and Skorch.


To reproduce the performance metrics of the best trained networks on the holdout test set: 

- download the contents of the google drive folder here: https://drive.google.com/drive/folders/1baMWx-K5wIKrFIZTR5HC0ib_JL8l_n0I
- this contains the two best trained networks (pickled), one each for MLP and CNN, which were too large to load to github.

- please open the jupyter notebook entitled ‘test_set_notebook.ipynb’.

- Make sure you have all of the requirements installed, which can be found in requirements.txt.

- Click cell, then click ‘run all’. The data set is too big to attach in my submission, but it can be downloaded directly in python as a torch.datasets object. The download of the test set, I have checked, takes around 15 minutes. Make sure the data folder is downloaded to the same folder as the test set notebook. Same goes for the .pkl files and .json files also in this submission, as these will need to be loaded on to the notebook. 

- All cells will run with no other input needed. Classification reports and visuals will be made to see results, and the parameters of the networks will also be printed. The CNN predictions can also take a few minutes, approximately 5. 
