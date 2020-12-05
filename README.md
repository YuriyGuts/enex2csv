# enex2csv

Convert Evernote ENEX files to CSV, optionally converting note content to Markdown.

Usage:
```
python enex2csv.py [-h] --input-file ENEXFILE --output-file CSVFILE [--use-markdown]
```

Example:
```
python enex2csv.py --input-file evernote.enex --output-file evernote.csv --use-markdown
```

CSV output fields:
* title
* content
* created_date
* updated_date
* reminder_date
* tags
