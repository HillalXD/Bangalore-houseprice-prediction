
# Bangalore housprice prediction

This project use to predict houseprice in Bangalore, you can get house predicted price by assign some features on app that linked with prediction model, This project are usefull for someone who want to search house in bangalore with spesific house parameter and price so they can calculate first before buy the house

## Install

This project requires **Python** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org/)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [Flask](https://flask.palletsprojects.com/)

## Usage

first, you can clone this git repository

```
git clone https://github.com/HillalXD/Bengaluru-houseprice-prediction.git
```

then navigate your command to this directory

```
cd Bengaluru-houseprice-prediction
```

after that open `app.py` to use flask webapp

```
python app.py
```

then add `/apidocs` on localhost url

```
http://127.0.0.1:5000/apidocs
```

## Code 
- Template code is provided in the `Bengaluru.ipynb` notebook file.
- `bengaluru.csv` in provide data source for training model
- `app.py` is flask web application to user input features for model predicting and return predicted price as output

## Dataset features

for doing prediction you need to input this features:

| features  | explanation  | 
| :-------- | :------- | 
|   bath | number of bath in house |
|bhk     | number of bedroom, hall and kicthen in house|
|sqft   | house size in squarefeet|


