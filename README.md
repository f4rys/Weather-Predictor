

# Weather AI predictor

<div>Machine learning project using <a href="https://github.com/facebook/prophet">Prophet</a> and data regarding every day from 1966 to present from <a href="https://danepubliczne.imgw.pl/">Instytut Meteorologii i Gospodarki Wodnej</a> to predict future weather conditions in Tarnów (Lesser Poland, PL). Project does not provide any useful information, as the weather is a very unstable and unpredictable factor. Consider this an educational project.</div>


<br/>

<div align="center">
  <p>
    <img src="https://imgur.com/VAzLpcZ.png"/>
  </p>
</div>

# 

## Used data
<div><a href="https://danepubliczne.imgw.pl/data/dane_pomiarowo_obserwacyjne/dane_meteorologiczne/dobowe/synop/">Historical weather data from IMGW website</a></div>

# 

## Used frameworks and libraries
<div>• <a href="https://jupyter.org/">Jupyter Notebook</a></div>
<div>• <a href="https://facebook.github.io/prophet/">Prophet</a></div>
<div>• <a href="https://joblib.readthedocs.io/en/latest/">Joblib</a></div>
<div>• <a href="https://pandas.pydata.org/">Pandas</a></div>
<div>• <a href="https://matplotlib.org/">Matplotlib</a></div>

# 

## Notebooks
<div>• <strong>Collecting weather data</strong> - downloads data files from IMGW website, concatenates them and prepares data for training</div>
<div>• <strong>Training and saving models</strong> - uses collected data to train models for predicting minimum temperature, maximum temperature and precipation, then saves them into models/ folder</div>
<div>• <strong>Making predictions</strong> - loads pretrained models to make predictions and draw plot for 30 days in the future</div>
