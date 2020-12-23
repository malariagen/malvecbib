# malvecbib

A bibtex bibliography for all things vaguely related to malaria vector
biology and genomics.

If adding new entries, please use the following conventions:

  1. Use author surname + year for the entry key, capitalising the
     surname, e.g., "Smith2009". If duplicate keys exist, suffix with
     a lower case letter, e.g., "Smith2009a", "Smith2009b", etc.

  2. Insert new entries in alphabetical order by entry key.

  3. Use abbreviated journal titles.

You can validate the file locally with biber by running:

```
$ biber --tool --validate-datamodel --dieondatamodel refs.bib
```

Contributions are welcome via pull requests.
