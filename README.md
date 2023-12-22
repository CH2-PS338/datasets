# Datasets

## Food Images
**LINK DATASET**
https://universe.roboflow.com/food-object-detection-test/track-meals-updated

### Overview
**CLASS**
- Alpukat
- Dada Ayam
- Jeruk
- Kangkung
- Nasi Merah
- Nasi Putih
- Salmon
- Sayur Bayam
- Telur Goreng
- Telur Rebus
- Tempe Goreng

Jeruk, Alpukat, and Pisang classes were obtained from the RoboFlow Universe dataset source. Meanwhile for the Dada Ayam, Kangkung, Nasi Merah, Nasi Putih, Salmon, Sayur Bayam, Telur Goreng, Telur Rebus, and Tempe Goreng, were obtained by scraping using Google image scraper and manual annotation.

## Food Nutritional Content
### Overview
**VARIABLES**
- NO : number of class
- CLASS : food classess
- KALORI : calories contained in food per 100 grams (gram)
- PROTEIN : proteins contained in food per 100 grams (gram)
- LEMAK : fats contained in food per 100 grams (gram)
- KARBOHIDRAT : carbohydrate contained in food per 100 grams (gram)
- AIR : water contained in food per 100 grams (gram)

This dataset was obtained from nilaigizi.com by entering the name of the food in the search column. We use macro nutrients for nutritional content, where there are 5 macro nutrients, namely protein, calories, fat, carbohydrates, and water.

## Nutritional Needs
### Overview
**VARIABLES**
- GENDER : male or female
- MIN UMUR : minimum age limit for class
- MAX UMUR : maximum age limit for class
- KALORI : number of calories needed in one day
- PROTEIN : number of proteins needed in one day
- LEMAK : number of fats needed in one day
- KARBOHIDRAT : number of carbohydrates needed in one day
- AIR : number of water needed in one day

We took this dataset manually on the Ministry of Health's website regarding Regulation of the Minister of Health of the Republic of Indonesia Number 28 of 2019 concerning Recommended Nutritional Adequacy Rates for Indonesian People.
