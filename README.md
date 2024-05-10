# TasteTuner
 TasteTuner - a customized recipe recommender

RUNNING ON A LOCAL MACHINE WITH JUPYTER NOTEBOOK

Setup

Before running the notebooks, ensure you have the following installed and downloaded:

1. Python 3.8 or higher
2. Jupyter Notebook or JupyterLab
4. Pip
3. Necessary Python packages: pandas, numpy, matplotlib, scikit-learn, networkx (Install via pip or conda)
4. Project directory (TasteTuner) containing all code and data files from here.

The following is the list of files in the TateTuner directory required to run the project:

Project Files

The project consists of the following notebooks:

1. Ingredient Network Analysis.ipynb - Start with this notebook to analyze ingredient relationships.
2. WordCloud.ipynb - Generate word clouds to visualize common terms in recipes.
3. Cuisine Rating.ipynb - Rate cuisines based on the analysis.
4. Recipe Classification.ipynb - Classify recipes into categories.
5. Ingredient-Based Recipe Clustering.ipynb - Cluster recipes based on ingredient similarity.
6. Recipe Difficulty Estimation.ipynb - Estimate the difficulty level of recipes.
7. Recipe Recommendation.ipynb - Recommend recipes based on user preferences.
8. RecipeSummarizer.ipynb - Summarize recipes extracting key information.

Data Files

The project consists of the following data files:

Ingredient Data.csv
Recipes.json
Yummly Clean.pkl

Execution

1. Open each .ipynb notebook. There are a total of 8 notebooks to run. They can be run in the order mentioned above.
2. Make sure the path to the data files in each notebook is correct is correct.
3. For each notebook, run the notebook cells sequentially or execute the entire notebook at once.

RUNNING WITH GOOGLE COLAB

Setup

1. Upload the Jupyter notebook files and any the 3 data files to your Google Drive.
2. Open each Jupyter notebook file in Google Colab.
3. If required, install any packages not available in Colab by running pip install commands within the notebook cells.
4. Mount your Google Drive to access the files using the below code:

from google.colab import drive
drive.mount('/content/drive')

5. Navigate to the project's directory on your Drive using the below command:

cd /content/drive/My Drive/path/to/TasteTuner/

Execution

1. For each notebook, execute the notebook either cell by cell or run the entire notebook in one go.
2. Adjust the paths and dependencies according to the specifics of your setup.
