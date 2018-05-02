# GRBZ Raw Data Processing

Almost every step has been carried out in the `data.ipynb` notebook.
The exceptions to this are minor fixes to the raw data extract (`raw_data/grb_table_1524584294.txt`), which were easier to fix in place, rather than with code.
The the corrected raw data is `raw_data/grb_table_1524584294_corr.txt`.

The final output data has been compiled into a number of formats for easy reuse:

* Tab delimited texts (`grbz_data.tar.gz`)
* Excel spreadsheet for easy viewing (`grbz_data.xlsx`)
* Python pickle (`grbz.pkl`)
* SQLite3 database file (compressed, `grbz_data.db.gz`)
