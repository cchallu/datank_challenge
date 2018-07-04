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
NYC trip record data.

| Field Name | Description |
| :---         | :---           |
| vendorid   | A code indicating the TPEP provider that provided the record.<br/> `1= Creative Mobile Technologies, LLC; 2= VeriFone Inc` |
| tpep_pickup_datetime   | The date and time when the meter was engaged. |
| tpep_dropoff_datetime   | The date and time when the meter was disengaged. |
| passenger_count   | The number of passengers in the vehicle.<br/>`This is a driver-entered value.` |
| trip_distance   | The elapsed trip distance in miles reported by the taximeter. |
| pickup_longitude   | Longitude where the meter was engaged. |
| pickup_latitude   | Latitude where the meter was engaged. |
| ratecodeid   | The final rate code in effect at the end of the trip.<br/> `1= Standard rate 2=JFK 3=Newark4=Nassau or Westchester 5=Negotiated fare 6=Group ride`    |
| store_and_fwd_flag   | This flag indicates whether the trip record was held in vehicle memory before sending to the vendor, aka “store and forward” because the vehicle did not have a connection to the server.<br/> `Y= store and forward trip N= not a store and forward trip` |
| dropoff_longitude   | Longitude where the meter was disengaged. |
| dropoff_latitude   | Latitude where the meter was disengaged.      |
| payment_type   | A numeric code signifying how the passenger paid for the trip. <br/> `1= Credit card 2= Cash 3= No charge 4= Dispute 5= Unknown 6= Voided trip` |
| fare_amount   | The time-and-distance fare calculated by the meter. |
| extra   | Miscellaneous extras and surcharges. Currently, this only includes the $0.50 and $1 rush hour and overnight charges. |
| mta_tax   | $0.50 MTA tax that is automatically triggered based on the metered rate in use. |
| improvement_surcharge   | $0.30 improvement surcharge assessed trips at the flag drop. The improvement surcharge began being levied in 2015.      |
| tip_amount   | amount – This field is automatically populated for credit card tips. Cash tips are not included.      |
| tolls_amount   | Total amount of all tolls paid in trip.      |
| total_amount   | The total amount charged to passengers. Does not include cash tips.      |

More information in: http://www.nyc.gov/html/tlc/html/about/trip_record_data.shtml

# Analysis
```console
local_user@local_host$ jupyter notebook source/datank_challenge.ipynb
```