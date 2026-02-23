# Data-Repository-for-the-effects-of-temperature-on-P.-tomentosa-development
This is a data repository for the manuscript titled: Temperature Influences Pseudocapillaria tomentosa Infections in Zebrafish (Danio rerio): Implications for Seasonality and Climate Change
Listed below discriptons for each dataset

cold_storage_infectivity_metadata

This dataset is associated with the larval fish infections with P. tomentosa eggs stored at 4°C for 14 days.

Column names are as follows

well: well-id associated with each fish 
worm.count: The number of worms detected via wet mout
fish.temp: The water temperature (°C) at which fish were kept at throughout the exposure
egg.temp: The temperature (°C) P. tomentosa eggs were stored at

egg_infectivity_larval_metadata

This dataset contatins the infection results of larval fish that were exposed to P. tomentosa eggs larvated at various temperatures.

Column names are as follows:
trial: The experimental trial conducted
plate: The plate-id associated with each fish
well: The plate well-id associated with each fish 
worm.count: The number of worms detected via wet mout
fish.temp: The water temperature (°C) at which fish were kept at throughout the exposure. 
egg.temp: The temperature P. tomentosa eggs were larvated at.

egg_larvation_metadata
This dataset is associated with evaluating the effects of water temperature on egg larvation.

Column names are as follows:
trial: The individual experiment conducted.
sample.id: The unique ID for each technical replicate in the dataset.
temperature: The incubation temperature (°C). Values designated as 4.28 or 13.28 indicate that eggs were incubated at 4 or 13 °C for 5 days and then held at 28 °C for an additional 5 days.
day: The day larvation was assessed after starting the incubation period.
larvated.eggs: The total number of larvated eggs in each sample.
unlarvated.eggs: The total number of unlarvatted eggs in each sample.

hot_exposure_adult_metadata
This dataset contatins the infection results of fish held at elevated temperatures (35°C).

Column names are as follows:
fish.id: Unique identifier for each fish in the dataset.
tank.id: The tank associated with each fish.
timepoint: The day post exposure a fish was evaluated
temperature: The tank water temperature (°C). “35.28” indicates that a fish was transferred back to 28°C at 25 days post exposure.
worm.count: The number of worms in each fish, including females.
female: The total number of gravid females in each fish.
mortality: Indicates if a fish was evaluated as a mortality < 3hr postmortem.

long_cold_exposure_adult_metadata
This dataset is contatins the infection results of fish held at lower temperatures (13°C) for ~ 100 days.

Column names are as follows:
tank.id: The tank associated with each fish
temp: The tank water temperature (°C). “13.28” indicates that a fish was transferred back to 28°C at 75 days post exposure
dpe: Days post exposure. When the fish were evaluated
fish.id: Unique identifier for each fish in the dataset
worm.burden: The total number of worms in each fish
sex: The sex of a specific worm
length: the length (µm) of a specific worm
comments: observations about each worm 
  
Dataset attributes: 
The dataset is formatted to display each worm’s length. Therefore, a the fish.id and worm.burden values will be repeated multiple times if a fish has multiple worms. 

qpcr_long_cold_exposure_adult_metadata
This dataset contains the P. tomentosa infection results of fish in the long term low temperature study using a qPCR diagonstic assay.

Column names are as follows:
dpe: Days post exposure. When the fish intestines were collected for qPCR analysis.
fish.id: Unique identifier for each fish in the dataset, corresponds to the fish.id in the long_cold_exposure_adult_metadata dataset.
temperature: The tank water temperature (°C).
qpcr_rep1: The first qPCR trial.
qpcr_rep2: The second qPCR trial.
diagnostic_result: The infection status of a fish given the qPCR result

short_cold_exposure_adult_metadata
This dataset is contatins the infection results from fish held at 13C for ~45 days.

Column names are as follows:
fish.id: Unique identifier for each fish in the dataset.
temp: The tank water temperature (°C). “13.28” indicates that a fish was transferred back to 28°C at 21 days post exposure.
tank.id: The tank associated with each fish.
dpe: Days post exposure. When the fish were evaluated.
inmature.worm: The total number of worms that could not be assigned a sex 
gravid.female: The number of gravid female worms







  


  


