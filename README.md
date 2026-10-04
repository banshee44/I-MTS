# I-MTS - Italian Medical Term Simplifications

### Overview 

### Data format
The resource is distributed as a UTF-8-encoded TSV file. The first row contains the column names, fields are separated by tab characters, and multiple values within the same field are separated by `|`. Empty fields indicate that no value is currently available.
### Data schema

| Column | Description |
|---|---|
| `id_loc` | Identifier of the source entry. Multiple identifiers are separated by '|'. |
| `term` | Medical term represented by the entry. |
| `simplification` | One or more simplified expressions. Multiple values are separated by '|'. |
| `type_of` | Broader term under which the entry is classified, when available. |
| `var` | Orthographic variants of the term, separated by '|'. |
### Multiple values
### Data generation and validation
### Version note
Following publication of the original paper, an additional review resulted in revisions to several entries and, in some cases, different classifications. The dataset published in this repository incorporates this second review and replaces the version described in the paper, which is not distributed separately. The paper remains the reference for the resource’s original methodology.

### Disclaimer
This resource was generated automatically and subsequently validated manually. Despite this review, it may still contain errors, omissions, or misclassifications.
As the data concern the medical domain, they should be used with caution and independently verified against authoritative sources. This resource is intended for research and informational purposes only and must not be used as a substitute for professional medical advice, diagnosis, treatment, or clinical judgment.
### Citation
### License
### Contact
