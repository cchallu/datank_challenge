# DATANK challenge

Dependencies:
- pandas
- jupyter
- ipython
- scipy
- sklearn
- matplotlib
- seaborn
- ggplot

# Python environment
```console
local_user@local_host$ conda env create -f datank_challenge.yml
```

# Data
Should be place in path './data/'
NYC trip record data. More information in:
http://www.nyc.gov/html/tlc/html/about/trip_record_data.shtml

| Field Name | Description |
| :---         | :---           |
| vendorid   | A code indicating the TPEP provider that provided the record.\       |
|            | 1= Creative Mobile Technologies, LLC; 2= VeriFone Inc              |
| tpep_pickup_datetime   |       |
| tpep_dropoff_datetime   |       |
| passenger_count   |       |
| trip_distance   |       |
| pickup_longitude   |       |
| pickup_latitude   |       |
| ratecodeid   |       |
| store_and_fwd_flag   |       |
| dropoff_longitude   |       |
| dropoff_latitude   |       |
| payment_type   |       |
| fare_amount   |       |
| extra   |       |
| mta_tax   |       |
| improvement_surcharge   |       |
| tip_amount   |       |
| tolls_amount   |       |
| total_amount   |       |
