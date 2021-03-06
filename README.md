# Plot-Maps-in-Python
A Data Visualization project that includes multitude of ways to plot locations on a Map.

### Setup (Using virtualenv)
1. Clone the repository to your system
```
git clone https://github.com/kb22/Plot-Maps-in-Python.git
```
2. Move into the cloned folder
```
cd Plot-Maps-in-Python
```
3. Download the data from [Kaggle](https://www.kaggle.com/darshank2019/business). Extract the zip. Rename the file as `dataset.csv` and save it to the folder `data` inside the directory `Plot-Maps-in-Python`
4. Create a virtual environment
```
virtualenv -p Python3 .
```
5. Activate the virtual environment
```
source bin/activate
```
6. Install all dependencies
```
pip install -r requirements.txt
```
7. Start Jupyter
```
jupyter notebook
```
8. Run the file `Plot Maps in Python.ipynb`

### Required API Keys
You will need two keys to make this work:
1. Google API Key: Create an account on https://console.cloud.google.com with a trial of 12 months and get access to the API key for Google Maps JavaScript API.
2. Plotly API Key: Create an account on https://plot.ly/feed/#/ and get an API Key.
