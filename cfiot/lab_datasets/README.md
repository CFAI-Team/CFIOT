# README

## Purpose

-   to download .z0\* files
-   unzip them back into a .csv file (~= 276 MB)

## Steps (under Ubuntu Linux command line for example)

-   download and **unzip** these files

-   cd to `lab_datasets/`

-   follow the steps (first zip to join splits, then unzip)

```shell
$ zip -s 0 lab_dataset.zip --output merged_dataset_forward_fill.zip
copying: merged_dataset_forward_fill.csv

$ unzip merged_dataset_forward_fill.zip
Archive:  merged_dataset_forward_fill.zip
  inflating: merged_dataset_forward_fill.csv

```

-   the `merged_dataset_forward_fill.csv` is the .csv for your study

## Why?

-   Due to the fact that GitHub only allows **maximum 25MB / per single file** imitation, we have to break down the original ~276MB .csv into smaller zip files to upload to GitHub repo.

-   Other than Linux command line; `WinRAR`, `7-Zip` or other file utilities under Windows and Mac should still do the zip merging job. Please help yourself Google / ChatGPT for steps.
