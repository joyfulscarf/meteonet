# MeteoNet : Data exploration toolbox

This repository is intended as a toolbox to handle the MeteoNet dataset. It's also a communication interface with MeteoNet's users : if  you have a request or a problem concerning MeteoNet, you can post an  [issue](https://github.com/meteofrance/meteonet/issues) on this project. For more information (installation, data types, glossary...), go to our [Slack workspace](https://tinyurl.com/meteonet-slack
) and/or check out our [documentation](https://meteofrance.github.io/meteonet/)! The data are also available on [Kaggle](https://www.kaggle.com/katerpillar/meteonet) with notebooks to help you explore, cross-check all data types! You can contribute to [challenges](https://www.kaggle.com/katerpillar/meteonet/tasks) and/or propose yours (time series prediction, rainfall nowcasting, observation data correction...etc)!

1. [What is MeteoNet ?](#meteonet)
2. [How to use this repository ?](#description)
3. [Installation](#installation)
4. [Licence](#licence)

# What is MeteoNet ?<a name="meteonet"></a>
  ![imageMeteoNet](docs_src/img/MeteoNet3img.png "Example of MeteoNet data")

MeteoNet is a meteorological dataset released by METEO FRANCE, the French national meteorological service. Our goal is to provide a clean and ready-to-use dataset for Data Scientist who want to try their hand on weather data.

The data spans over 3 years, 2016 to 2018, and covers two geographical areas : the north-western and south-eastern quarters of France.

The dataset regroups ground station observations, land-sea and relief masks, radar observation, weather models forecasts and satellite data. 

# How to use this repository ?<a name="description"></a>

This toolbox includes **data samples** from MeteoNet, the **meteonet_toolbox package** with some useful tools and **notebooks** to help you explore and cross-check all data types.

The notebooks should help you open each data type (grid and point data, different resolutions...) and visualize it with map and relief overlays.

The notebooks rely on the meteonet_toolbox package and we recommend that you install it.


# Installing the toolbox<a name="installation"></a>

All the install instructions for our toolbox are available [here](https://meteofrance.github.io/meteonet/english/install/) in our documentation.

# Licence <a name="licence"></a>

The Dataset is licenced by METEO FRANCE under [Etalab Open Licence 2.0](https://github.com/meteofrance/meteonet/blob/master/LICENCE.md).

When using this dataset, please cite:
<br/>Gwennaëlle Larvor, Léa Berthomier, Vincent Chabot, Brice Le Pape, Bruno Pradel, Lior Perez. **MeteoNet, an open reference weather dataset by METEO FRANCE**, 2020