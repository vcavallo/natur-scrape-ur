# Natur Scrape-ur

1. have python3 installed (probably 3.5 or nearby)
2. run `pip3 install requests beautifulsoup4 openpyxl`
3. put a .xlsx file adjacent to the `scrape.py` script
4. run `python3 scrape.py <your-xlsx-filename> output.xlsx` (you can name the output file whatever you want, `output.xlsx` is an example)

# Caveats:

- this is an extremely low-effort first attempt.
- only works with .xlsx files
- scientific name must be in first column for now
- scrapes the public web of the services - no APIs yet
