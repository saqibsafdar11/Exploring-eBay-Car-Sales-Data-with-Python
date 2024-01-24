# Exploring eBay Car Sales Data
 Python used to clean and analyse data

The aim of this project is to clean the data and analyze the included used car listings.
In this project we will work with a dataset of used cars from eBay Kleinanzeigen, a classifieds section of the German eBay website.

We will be working on a dataset of used cars from *eBay Kleinanzeigen*, a [classifieds](https://en.wikipedia.org/wiki/Classified_advertising) section of the German eBay website.

The dataset was originally scraped and uploaded to [Kaggle](https://www.kaggle.com/orgesleka/used-cars-database/data).  The version of the dataset we are working with is a sample of 50,000 data points that was prepared by [Dataquest](https://www.dataquest.io) including simulating a less-cleaned version of the data.

The data dictionary provided with data is as follows:

- `dateCrawled` - When this ad was first crawled. All field-values are taken from this date.
- `name` - Name of the car.
- `seller` - Whether the seller is private or a dealer.
- `offerType` - The type of listing
- `price` - The price on the ad to sell the car.
- `abtest` - Whether the listing is included in an A/B test.
- `vehicleType` - The vehicle Type.
- `yearOfRegistration` - The year in which which year the car was first registered.
- `gearbox` - The transmission type.
- `powerPS` - The power of the car in PS.
- `model` - The car model name.
- `kilometer` - How many kilometers the car has driven.
- `monthOfRegistration` - The month in which which year the car was first registered.
- `fuelType` - What type of fuel the car uses.
- `brand` - The brand of the car.
- `notRepairedDamage` - If the car has a damage which is not yet repaired.
- `dateCreated` - The date on which the eBay listing was created.
- `nrOfPictures` - The number of pictures in the ad.
- `postalCode` - The postal code for the location of the vehicle.
- `lastSeenOnline` - When the crawler saw this ad last online.


The following tasks were performed:

1. Data Cleaning:
   - The dataset of used cars from eBay Kleinanzeigen was imported.
   - The column names were cleaned and converted to snake case.
   - The "price" and "odometer" columns were cleaned and converted to numeric data types.
   - Outliers in the "price" and "registration_year" columns were removed.
   - Invalid values in the "registration_year" column were filtered out.

2. Exploratory Data Analysis:
   - The distribution of dates in the "date_crawled", "ad_created", and "last_seen" columns was analyzed.
   - The distribution of car prices and mileage by brand was analyzed.
   - The relationship between mean mileage and mean price for the top 10 brands was visualized.

Overall, this notebook focused on cleaning the data and performing exploratory analysis on the used car dataset.