# Releasing the dataset

## Recreate the raw data from glottography-data

In case of upstream changes in glottography-data:
```shell
cldfbench download cldfbench_dedio2019britain.py
```

## Recreate the CLDF data

```shell
cldfbench makecldf cldfbench_dedio2019britain.py --glottolog-version v5.2
cldfbench cldfreadme cldfbench_dedio2019britain.py
cldfbench zenodo cldfbench_dedio2019britain.py
cldfbench readme cldfbench_dedio2019britain.py
```

## Validation

```shell
cldf validate cldf
```

```shell
cldfbench geojson.validate cldf
```

```shell
cldfbench geojson.glottolog_distance cldf --format pipe
```

| ID | Distance | Contained | NPolys |
|:---------|-----------:|:------------|---------:|
| bret1244 | 0.00 | True | 1 |
| corn1251 | 0.05 | False | 1 |
| dani1285 | 0.00 | True | 1 |
| dutc1256 | 0.00 | True | 1 |
| faro1244 | 0.00 | True | 1 |
| icel1247 | 0.00 | True | 1 |
| iris1253 | 1.38 | False | 6 |
| manx1243 | 0.00 | True | 1 |
| midd1317 | 0.00 | True | 1 |
| midd1318 | 0.00 | True | 1 |
| midd1321 | 0.00 | True | 1 |
| midd1343 | 0.00 | True | 1 |
| nort2626 | 0.03 | False | 1 |
| nort2628 | 0.00 | True | 1 |
| norw1258 | 0.00 | True | 1 |
| oldd1237 | 0.00 | True | 1 |
| olde1238 | 0.00 | True | 1 |
| oldf1239 | 0.00 | True | 1 |
| oldf1241 | 0.00 | True | 1 |
| oldh1241 | 1.54 | False | 1 |
| oldi1245 | 0.00 | True | 1 |
| oldn1244 | 0.00 | True | 14 |
| olds1250 | 0.00 | True | 1 |
| oldw1239 | 0.00 | True | 1 |
| pica1241 | 0.00 | True | 1 |
| scot1243 | 0.00 | True | 1 |
| scot1245 | 0.00 | True | 1 |
| stan1290 | 0.00 | True | 3 |
| stan1293 | 0.00 | True | 1 |
| stan1295 | 0.00 | True | 1 |
| wels1247 | 0.00 | True | 1 |
