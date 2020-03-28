# Clustering of São Paulo Subway Stations using Foursquare API
The repository will include code for the project. This includes data, notebooks and reports.


### Capstone Project description
At this notebook, Foursquare API was used to cluster subway station (Metro) neighborhoods in Sao Paulo regarding closely venues. The amount of venues per category in each subway station was acquired by a HTTP request to Foursquare API, and then used to group the stations into clusters. For this notebook k-means clustering algorithm was selected to complete this task. Finally, Folium library has been used to visualize the neighborhoods in Sao Paulo and their emerging clusters.

- [Report]()
- [Notebook](https://github.com/felipetestaaa/ml-sao-paulo-subway-clustering/blob/master/notebook/SaoPauloClustering.ipynb)
- [Article - Medium Post](https://medium.com/@felipe.testaa/unsupervised-machine-learning-kmeans-clustering-of-s%C3%A3o-paulo-subway-stations-using-foursquare-c5101727dd85)

### Set up
1. Clone the repository
```
git clone git@github.com:felipetestaaa/ml-sao-paulo-subway-clustering.git
```
2. Move inside the newly created repository
```
cd ml-sao-paulo-subway-clustering
```
3. Create a virtual environment and activate it
```
virtualenv -p python3 .venv
```
4. Activate the virtual environment
```
source .venv/bin/activate
```
5. Install all libraries
```
pip install -r requirements.txt
```
6. Start jupyter
```
jupyter notebook
```
7. Deactivate environment (if created and activated before)
```
deactivate
```
