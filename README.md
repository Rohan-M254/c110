# Sampling Distribution Exercise

A Python exercise that visualises the distribution of reading times and compares it with the distribution of means from repeated samples.

## Project structure

- `c110/mean.py` — plots reading times, draws repeated samples, and reports the sampling mean.
- `c110/medium_data.csv` — input dataset containing a `reading_time` column.

## Requirements

```bash
pip install pandas plotly
```

## Run

Run from the `c110` directory:

```bash
python mean.py
```

The script currently uses random sampling and does not set a seed, so results vary between runs. The dataset's source and units are not specified in the original project.