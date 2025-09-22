# Glottography dataset derived from Dedio et al. 2019 "Evidence for Britain and Ireland as a Linguistic Area"

[![CLDF validation](https://github.com/Glottography/dedio2019britain/workflows/CLDF-validation/badge.svg)](https://github.com/Glottography/dedio2019britain/actions?query=workflow%3ACLDF-validation)

## How to cite

If you use these data please cite
- the original source
  > Dedio, Stefan, Peter Ranacher & Paul Widmer. 2019. Evidence for Britain and Ireland as a Linguistic Area. Language 95(3). 498–522. doi: 10.1353/lan.2019.0054.
- the derived dataset using the DOI of the [particular released version](../../releases/) you were using

## Description


This dataset provides overlapping, approximate ranges for Indo-European languages spoken in the British Isles between 800 and 1900 AD.

This dataset is licensed under a CC-BY-4.0 license




### Coverage

```geojson
{"type": "Feature", "geometry": {"type": "Polygon", "coordinates": [[[-25.3, 42.3], [-25.3, 71.3], [31.3, 71.3], [31.3, 42.3], [-25.3, 42.3]]]}, "properties": {}}
```


### Focal year

The source of this dataset investigates the extension of language areas at three distinct epochs
which translate to three different values for the `Year` column in the dataset's `ContributionTable`.
However, these distinct epochs are also almost always reflected in the assigned Glottolog languoid.
E.g. for English, the polygons are assigned to *Old English*, *Middle English* and *English*.


## CLDF Datasets

The following CLDF datasets are available in [cldf](cldf):

- CLDF [Generic](https://github.com/cldf/cldf/tree/master/modules/Generic) at [cldf/Generic-metadata.json](cldf/Generic-metadata.json)