The dataset was taken from [Kaggle](https://www.kaggle.com/c/nyc-taxi-trip-duration/data?select=train.zip) and contains the following columns:

- Pickup and Dropoff Datetime: The timestamp for the start and end of each trip.
- Pickup and Dropoff Coordinates: Latitude and longitude data, which allows for the calculation of trip distance.
- Passenger Count: The number of passengers, which can impact the likelihood of shared rides or detours.
- Trip Duration: Derived from the pickup and dropoff times, this is the primary variable to be predicted.
- Fare and Payment Details: While not central to this study, these details provide insight into the economic aspect of taxi operations.