Requirment:
Python to to support API
Flask to build API
Pyscopg2 for database connect 
Postgresql for Data Base
Dbeaver to see GUI database

for First API:
URL: http://127.0.0.1:5000/vehicle_price?vehicle=activa&year=2006&damage=break&damage1=hand
Use this url to get final price after deduction of amount base on year or damage
for 1 year : 5%
for 1 damage : 2%
for 2 damage : additional 2%

I have consider 2005 is default start date

For Second:
URL : http://127.0.0.1:5000/price_base_on_colour?vehicle=activa&colour=red
Use this url to get price base on colour


For Third:
URL : http://127.0.0.1:5000/all_model?vehicle=activa
Use this to get all model related to vehicle name 