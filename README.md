# Package `org.Qsuber.eg.db`

**Date:** August 11, 2024

## Title

**Genome wide annotation for Quercus suber**

## Description

Genome wide annotation for *Quercus suber*, primarily based on mapping using Entrez Gene identifiers.

## Version

0.99.0

## Author

Mauri-Panadero N.

## Maintainer

Mauri-Panadero N. <nuriamauriphd@gmail.com>

## Depends

- R (>= 2.7.0)
- methods
- AnnotationDbi (>= 1.48.0)

## Suggests

- DBI
- annotate
- RUnit

## Imports

- methods
- AnnotationDbi

## License

Artistic-2.0

## Organism

*Quercus suber*

## Species

*Quercus suber*

## BiocViews

- OrgDb
- annotation

---

## R Topics Documented

- `org.Qsuber.eg.db`
- `org.Qsuber.egORGANISM`
- `org.Qsuber.eg_dbconn`

---

## Index

1. **org.Qsuber.eg.db**
2. **org.Qsuber.egORGANISM**
3. **org.Qsuber.eg_dbconn**

---

## Bioconductor Annotation Data Package

### Description

Welcome to the `org.Qsuber.eg.db` annotation package. This is an organism-specific package. The purpose is to provide detailed information about the species abbreviated in the second part of the package name `org.Qsuber.eg.db`. This package is updated biannually.

To learn more about this package, users are encouraged to learn about the `select`, `columns`, `keys`, and `keytypes` methods. These are described in a walkthrough on the Bioconductor website as well as in the manual pages and vignettes in the `AnnotationDbi` package.

---

## `org.Qsuber.egORGANISM`

### Description

`org.Qsuber.egORGANISM` is an R object that contains a single item: a character string that names the organism for which `org.Qsuber.eg` was built.

### Details

Although the package name is suggestive of the organism for which it was built, `org.Qsuber.egORGANISM` provides a simple way to programmatically extract the organism name.

### See Also

- `AnnotationDb-class` for use of the `select()` interface.

### Examples

```r
## select() interface:
## Objects in this package can be accessed using the select() interface
## from the AnnotationDbi package. See ?select for details.

## Bimap interface:
org.Qsuber.egORGANISM
