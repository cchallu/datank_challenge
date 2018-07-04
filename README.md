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
| vendorid   | A code indicating the TPEP provider that provided the record.<br/> `1= Creative Mobile Technologies, LLC; 2= VeriFone Inc` |
| tpep_pickup_datetime   | The date and time when the meter was engaged. |
| tpep_dropoff_datetime   | The date and time when the meter was disengaged. |
| passenger_count   | The number of passengers in the vehicle. `This is a driver-entered value.` |
| trip_distance   | The elapsed trip distance in miles reported by the taximeter. |
| pickup_longitude   | Longitude where the meter was engaged. |
| pickup_latitude   | Latitude where the meter was engaged. |
| ratecodeid   | The final rate code in effect at the end of the trip.<br/> `1= Standard rate 2=JFK 3=Newark4=Nassau or Westchester 5=Negotiated fare 6=Group ride`    |
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
