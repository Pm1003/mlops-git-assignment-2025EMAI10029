# Dataset: Palmer Penguins

## Source

UCI Machine Learning Repository

## Species

- Adelie
- Gentoo
- Chinstrap

## Summary

- **Number of samples:** 344
- **Number of features:** 8 (after preprocessing)
- **Target variable:** sex (Male/Female - Binary Classification)

## Column Names and Types

```
species               object
island                object
bill_length_mm       float64
bill_depth_mm        float64
flipper_length_mm    float64
body_mass_g          float64
sex                   object
year                   int64
dtype: object
```

## Missing Values Analysis

```
species               0
island                0
bill_length_mm        2
bill_depth_mm         2
flipper_length_mm     2
body_mass_g           2
sex                  11
year                  0
dtype: object

Total missing values: 19
```
