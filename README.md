# BigData HW4
# Problem 1.2: Power of Random Forests

## Required Packages and Frameworks:
* ```python (preferably 3.0+)```
* ```numpy```
* ```pandas```
* ```sklearn```
* ```time```
* ```matplotlib```
* ```notebook```

## To run my code (jupyter notebook) you can run it either in Google Colab or Locally.

### To run in Google Colab: 
* Go to this link: https://colab.research.google.com/drive/1Ofc_gQQZwRD-pFYEXiPDuDwQtOml3JAX?usp=sharing
* Make a copy of the notebook.
* Once you've opened the notebook, click the folder icon at the very left, looks like this:
  * ![image](https://github.com/nchhaj189/BigData-HW2/assets/15990293/8fbff43e-f1b4-4275-94d4-e31761084926)
* Then you click the file icon with an arrow in it:
  * ![image](https://github.com/nchhaj189/BigData-HW2/assets/15990293/23eb0787-7329-48ea-9aec-70079372ecae)
* This will allow you to select a file to upload from your computer. Navigate to the ```winequality-red.csv``` dataset under the ```Data/``` folder of this project, and upload it.
* From here you can just run all the cells in the notebook, everything should work fine, if it doesn't you might need to adjust the line in the cell where it says ```df = pd.read_csv('/winequality-red.csv')```, but that path should be correct for colab if you uploaded the data correctly as shown in the previous screenshot.
 
 ### To run locally:
 * Install python (if not already installed) and ensure all the packages listed in the required packages section above are installed. All these packages can be installed with the ```pip install``` command. For example to install numpy you just do: ```pip install numpy```, and then replace numpy with all the other packages to install them all using pip install.
 * Open a terminal and navigate to the this project directory.
 * As long as you installed ```notebook``` you should be able to run the ```jupyter notebook``` command, which will open a browser with jupyter. From there you should be able to see my notebook ```Nipun-BigDataHW4.ipynb```, open the notebook.
 * All you have to do here is to change the path to the dataset, in the cell of notebook where it says ```df = pd.read_csv('/winequality-red.csv')```, to be the absolute path to the ```winequality-red.csv``` file (so like the path that includes C: if on windows).
 * Once that is done, you can just run the notebook, and as long as everything is installed correctly it should work.

