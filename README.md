# json-mining
## Extracting useful infromation from json file on NGS QC output

This script extracts total base after and before filtering, and does calculation as follow
result = total_base - total_base * duplcation_rate
It returns result for every filtering stage

### Usage:
./json myjson.json

