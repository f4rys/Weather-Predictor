# Weather predictor

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) 

<div>Machine learning project using <a href="https://github.com/facebook/prophet">Prophet</a> and data regarding every day from 1966 to the present from <a href="https://danepubliczne.imgw.pl/">Instytut Meteorologii i Gospodarki Wodnej</a> to predict future weather conditions in Tarnów (Lesser Poland, PL). The project does not provide any useful information, as the weather is a very unstable and unpredictable factor. Consider this as an educational project only.</div>

<br/><div align="center"><img src="./example.png"/></div>

## Used data
<div><a href="https://danepubliczne.imgw.pl/data/dane_pomiarowo_obserwacyjne/dane_meteorologiczne/dobowe/synop/">Historical weather data from IMGW website</a></div>


## Used frameworks and libraries
<div>• <a href="https://jupyter.org/">Jupyter Notebook</a></div>
<div>• <a href="https://facebook.github.io/prophet/">Prophet</a></div>
<div>• <a href="https://joblib.readthedocs.io/en/latest/">Joblib</a></div>
<div>• <a href="https://pandas.pydata.org/">Pandas</a></div>
<div>• <a href="https://matplotlib.org/">Matplotlib</a></div>

## Notebooks
<div>• <strong>Collecting weather data</strong> - downloads data files from IMGW website, concatenates them and prepares data for training</div>
<div>• <strong>Training and saving models</strong> - uses  collected data to train models for predicting minimum temperature,  maximum temperature and precipitation, then saves them into models/ folder</div>
<div>• <strong>Making predictions</strong> - loads pre-trained models to make predictions and draw plots for 30 days in the future</div>
