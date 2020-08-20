# malvecbib

A bibtex bibliography for all things related to malaria vector biology
and genomics.

If adding new entries, please observe the following conventions:

  1. Use author surname + year for the entry key, capitalising the
     surname, e.g., "Smith2009". If duplicate keys exist, suffix with
     a lower case letter, e.g., "Smith2009a", "Smith2009b", etc.

  2. Insert new entries in alphabetical order by entry key.

  3. It is suggested to remove the abstract field to keep the file
     more compact.

  4. Please use abbreviated journal titles.

You can validate the file locally with biber by running:

```
$ biber --tool --validate-datamodel --dieondatamodel refs.bib
```

Contributions are welcome via pull requests.
