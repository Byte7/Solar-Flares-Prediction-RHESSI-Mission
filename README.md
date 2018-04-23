# Solar-Flares-Prediction-RHESSI-Mission

## The initial steps taken in the preprocessing are as follows -
1. The dataset was taken from NASA RHESSI Data [repository](https://hesperia.gsfc.nasa.gov/rhessi_data_search/rhessi_data_search_vme.html) accessed through a web form.
2. The initial format of files was FITS. This was converted to CSV by using tools provided [here](https://fits.gsfc.nasa.gov/fits_viewer.html).
3. The many csv files generated from the FITS files were concatenated to make the current dataset in the [repository](https://github.com/Byte7/Solar-Flares-RHESSI-Mission/tree/master/data). [This](https://github.com/Byte7/Solar-Flares-RHESSI-Mission/tree/master/Join_script) script was used for the same.

## Results
Our Top 3 models' results for prediction of a energy range of a solar flare based on attributes of the flare are -
1. Gradient Boosting Classifier - 87 % accuracy
2. Random Forests Classifier - 86 % accuracy
3. Decision Tree Calssifier - 82 % accuracy

### A detailed blog post is available [here](https://byte7.github.io/blog/Predicting-SolarFlares/) explaining how I went around the data and prediction of flare's energy.
