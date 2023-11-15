# Tipps
 bash data_collection/bashs/weather-3/routes_town01_long.sh > >(tee ./stdout.out) 2> >(tee ./error.out)
python class.py   2>&1 | tee  result.log
