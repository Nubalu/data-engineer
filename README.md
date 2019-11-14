# Data Engineer Technical Test

### Introduction

Welcome to Nubalū technical test for Data Engineer position. The purpose of this test is both evaluate your programming skills and engineering vision according to our offer posted [here](https://nubalu.io/jobs/data-engineer).

So, main responsibilities of this position are:

1. Find the way to automate data extraction from public/private sources.
2. Transform it into consumable data for Data Scientists (without loosing raw data).
3. Make this data available by loading it on databases or AWS.

This data pipeline if fully implemented with Python3 scripts running over AWS Lambdas, using UNIX tools if no Python solution is possible.

### Description

As we said, the purpose of this test is evaluate your technical skills, so we have raised a simple ETL problem which shouldn't take more than **1-2 hours** to solve this test, so we understand non top quality code ;)

You have to develop first two steps of the pipeline **fully automated** in a single Python3 script, using necessary libraries like `json` or `requests`.

1. Go to this [INE data source](https://www.ine.es/jaxiT3/Tabla.htm?t=22356&L=0) and extract (non manual download) all available data of *Indice de Precios de Consumo. Base 2016* (all provinces, subgroups, data types and months).

2. Give some logic structure to this data aiming to posterior queries like:

   ```json
   In [1]: data["02 Albacete"]["011 Alimentos"]["Índice"]["2019M01"]
   Out[1]: 100.396
   ```

3. Export structured data into a JSON file.

4. Make available both `.py` and `.json` file on any personal repository, Dropbox or similar collaborative tools (including a `README.md` for briefly explaining your work is a plus).

If you have any doubt, please feel free to contact us at jobs@nubalu.io.



Best regards.

The Nubalū Team.