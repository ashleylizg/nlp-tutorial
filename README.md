# nlp-tutorial
Divide and prepare Amazon product reviews for food items for Natural Language Toolkit (NLTK) to train a classifier for sentiment analysis to determine positive and negative reviews.

**Data Source**: Grocery and Gourmet Food section of [Amazon Review Data (2018)](https://nijianmo.github.io/amazon/index.html) from Jianmo Ni, UCSD

Due to the size of this file, it must be downloaded and unzipped per use and is not included in this repository. The data folder is empty but can be used for this locally.

## Running locally

```powershell
git clone <this_repo>
cd nlp-tutorial

# (optional) Set up a virtual environment at /env
python -m venv env
# Then this should activate it in Powershell or a Unix terminal
./env/scripts/activate

# Install the requirements
pip install -r requirements.txt

# Run the Jupyter Notebook and select the main.ipynb file
jupyter notebook

# Then exit the virtual environment
deactivate

For future runs:
```powershell
cd nlp-tutorial
./env/scripts/activate
jupyter notebook
# When finished, use Ctrl+C to kill the Jupyter Notebook
deactivate
```
