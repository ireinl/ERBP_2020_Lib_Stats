# Readme

This dataset was created for a course at the iSchool at the University of Washington in the spring of 2021. It is a dataset describing library usage based on three metrics for all 14 pubilc library branches within the East Baton Rouge Parish public library system for the year 2020. The metrics are gate count, computer usage, and circulation. The intended audience is municipal and library policymakers. It is freely available to the public and the dataset is available .csv format.

## Table of Contents

- [Naming](#Naming)
- [Normalization](#Normalization)
- [Data Dictionary](#datadictionary)
- [Metadata](#metadata)
- [Security](#security)
- [Contact](#contact)

## Naming

The naming convention should be as follows: LibrarySystem_Year_Description_Of_Data

For example, another dataset following this convention might be: EBRP_2021_Circulation_Stats

## Normalization

These data have been curated from open data released by East Baton Rouge Parish public libraries, which can be found here: https://catalog.data.gov/dataset/ebrp-library-circulation-statistics, https://catalog.data.gov/dataset/ebrp-library-gate-counts, https://catalog.data.gov/dataset/ebrp-library-computer-usage-stats. Monthly usage data from these statistics were summed to create yearly information about each library's usage throughout the year 2020. Not all months were entered concurrently in the original datasets and required the interested party to scroll through the full data to find a particular month. Compiling monthly data into yearly data is designed to be a quick snapshot of each library's metrics in 2020. Data have been mad to conform to the data dictionary described below.

## Data Dictionary


| **Variable** | **Variable Name** | **Measurement Unit** | **Allowed Values** | **Definition** |
| --- | --- | --- | --- | --- |
| **LIBRARY_NAME** | Name of Library | String | East Baton Rouge Parish Library Names | Name of the library branch |
| **GATE_COUNT** | Library Gate Count | Numerical | Integers greater than 0 | Count of people entering the library branch |
| **CIRCULATION** | Materials Circulation | Numerical | Integers greater than 0 | Count of items circulated by the library branch |
| **COMPUTER_USAGE** | Computer Usage | Numerical | Integers greater than 0 | Count of computer usage at the library branch |


## Metadata
Schema Used: Dublin Core--output as XML (with assistance from https://nsteffel.github.io/dublin_core_generator/generator_nq.html#format)


    >

    xmlns:dc="http://purl.org/dc/elements/1.1/">
    <dc:title>EBRP 2020 Lib Stats</dc:title>
    <dc:creator>Ian Reinl</dc:creator>
    <dc:creator>https://www.linkedin.com/in/ireinl/</dc:creator>
    <dc:subject>East Baton Rouge Parish public library</dc:subject>
    <dc:description>This is a dataset describing library usage based on three metrics for all 14 pubilc library branches within the East Baton Rouge Parish public library system for the year 2020. The metrics are gate count, computer usage, and circulation.</dc:description>
    <dc:date>2021-03-08</dc:date>
    <dc:type>Dataset</dc:type>
    <dc:type>http://purl.org/dc/dcmitype/Dataset</dc:type>
    <dc:format>csv</dc:format>
    <dc:format>https://tools.ietf.org/html/rfc7111</dc:format>
    <dc:identifier>https://github.com/ireinl/ERBP_2020_Lib_Stats#erbp_2020_lib_stats</dc:identifier>
    <dc:source>https://catalog.data.gov/dataset/ebrp-library-circulation-statistics</dc:source>
    <dc:source>https://catalog.data.gov/dataset/ebrp-library-gate-counts</dc:source>
    <dc:source>https://catalog.data.gov/dataset/ebrp-library-computer-usage-stats</dc:source>
    <dc:language>en</dc:language>
    <dc:coverage>http://vocab.getty.edu/page/tgn/2000870</dc:coverage>
    <dc:rights>https://unlicense.org/</dc:rights>



## Security

These data are freely available to the public.

## Contact
Ian Reinl
ireinl@uw.edu

