* How To Use this project?
___________________________________________________________________________________________________________________________________________

* Pre-requisites:

1. First Clone/Download this repository
2. Install anaconda if not already installed in your computer
3. `cd` (change directory from cmd line) to where you've downloaded this project, into this directory
4. Create a conda environment using following command:
    `conda create --prefix ./env pandas numpy matplotlib scikit-learn`
    Press `y` and `enter` to confirm  
5. See List of availble conda environments and activate yours using following commands:
    `conda env list`
    `conda activate {your_env_from_list}`
6. Install Juyter, TextBlob, pickle and seaborn packages using following commands:
    `conda install jupyter`
    Press `y` and `enter` to confirm  
    `conda install -c conda-forge textblob`
    Press `y` and `enter` to confirm  
    `conda install -c conda-forge pickle5`
    Press `y` and `enter` to confirm 
    `conda install -c anaconda seaborn`
    Press `y` and `enter` to confirm 
7. Deactivate the conda environment using:
    `conda deactivate`
8. Exit the terminal or cmd line

___________________________________________________________________________________________________________________________________________

* How to Start Using Project:

___________________________________________________________________________________________________________________________________________

1. Once all the steps from pre-requisites are done, `cd` (change directory from cmd line) to where you've downloaded this project, into this directory.
2. See List of availble conda environments and activate yours using following commands:
    `conda env list`
    `conda activate {your_env_from_list}`
3. Start Jupyter notebook using
    `jupyter notebook`
4. Now Once UI for jupyter notebook is open in your browser, Execute Following Notebooks(From this directory) in order within jupyter UI:
    `Data_Preparation.ipynb`  -- It will create, clean and label the data to be used for training the model.
    `Data_Visualization.ipynb` -- It will Help to understand and visualize distribution range and variety of prepared data.(This is optional if you don't want to see it)
    `Data_Modeling.ipynb` -- This one is actually responsible for creating and training models on prepared datasets
    `Data_Model_Evaluation.ipynb` -- This one will evauate the most efficient model on various metrices and will plot graphs to visualize the evaluation results. This also provides playground to test our model at real time.
5. Once You are done with testing and visualizing data; Simply close browser and return to terminal
6. In terminal press `ctrl + c` and then press `y` and `enter` to stop jupyter process.
7. Deactivate the conda env using:
    `conda deactivate`
8. Exit from the terminal once done.
9. From next time you can simply activate environment, start jupyter notebook and start from `Data_Modeling.ipynb` or `Data_Model_Evaluation.ipynb` notebook if you don't want to do data preparation and visualization step again

