
# Multi-Model Framework for Toxic Comment Classification


## Data set Details

The dataset provided in the Dataset folder inside Project folder: The datasets would be in folder: "Multi_Model_Framework_for_Toxic_Classication/Dataset" contains two csv files named "data.csv" and "train.csv"

While the running the project locally, place the datasets in the same folder as the project (ipynb) file.

Dataset is also available to download from: https://drive.google.com/drive/folders/1Xz6AOiNRohJDwIeQe0n9HC_RnH7F5a_K?usp=sharing
## Installing Necessary Libraries

Before running the project, install the following Libraries using the command: 

    'pip install <library-name>'

List of Libraries to be installed:

    1. tensorflow
    2. pandas
    3. matplotlib
    4. seaborn
    5. nltk
    6. wordcloud
    7. scikit-learn
    8. numpy
    9. gensim
    10. scipy
    11. textblob

## Steps to run the project locally:

    1. Keep the dataset in the same folder as the ipynb file.
    2. Install all the above mentioned Libraries.
    3. Now before running the project's notebook file, change the path of all the datasets in the notebook to your current directory.
    4. Run the project's ipynb file on Jupyter or anyother other similar IDE.

## Steps to run the project on Google Colabs:

    1. Upload the given .ipynb file on Google Colabs [https://colab.research.google.com/]
    
    2. Install all the above mentioned Libraries.

    3. Uncomment the following line in the ipynb file in the 2nd cell: 
        from google.colab import drive
        drive.mount("/drive", force_remount=True)
    
    4. Now upload the dataset given in folder Dataset to Google Drive as per the path: "/drive/My Drive/NLP/<dataset>".

    5. Change the path for df1 and df2 in 4th cell accordingly.
        For Example: 
        df1 = loadDataset('/drive/My Drive/NLP/data.csv')
        df2 = loadDataset('/drive/My Drive/NLP/train.csv') 

    6. Run the project on Google Colabs.


