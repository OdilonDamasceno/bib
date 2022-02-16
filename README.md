# BIB

Bib is a script to download citation based on [DOI](https://www.doi.org/)

## Dependencies 

[wget](https://www.gnu.org/software/wget/) to make requests

## Usage

The script will download the citation and append to default bib file location (~/citations.bib). But you can change the default location setting the `BIBFILE` variable (I recommend in ~/.bashrc or something like that). 

### Basic usage

```bash
bib <DOI>
```

### Setting `BIBFILE`

```bash
BIBFILE=~/Documents/citations.bib bib <DOI>
```

## LICENCE

MIT