# ETL Process Script

This Python script performs an ETL (Extract, Transform, Load) process for data files in CSV, JSON, and XML formats. It extracts data from these files, transforms the data by converting units, and loads the transformed data into a CSV file. The script also logs the progress of each phase of the ETL process.

## Table of Contents

- [Requirements](#requirements)
- [Usage](#usage)
- [Functions](#functions)
  - [extract_from_csv](#extract_from_csv)
  - [extract_from_json](#extract_from_json)
  - [extract_from_xml](#extract_from_xml)
  - [extract](#extract)
  - [transform](#transform)
  - [load_data](#load_data)
  - [log_progress](#log_progress)
- [Example Log](#example-log)

## Requirements

- Python 3.x
- Pandas
- Glob
- XML (built-in Python library)
- datetime (built-in Python library)

You can install the required packages using:

```bash
pip install pandas
