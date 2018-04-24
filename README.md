# Overview of Semi-Supervised Classification with GCNs

Materials for technical overview of 'Semi-Supervised Classification
with GCNs' by Kipf & Welling (2017) given as an invited talk
at ML6 in Ghent, Belgium 24 April, 2018.

## Installation

The dependencies to run the notebooks are:

- `numpy`
- `scipy`

## Usage

The slides for this talk can be generated via:

```bash
jupyter nbconvert overview_ssc_gcn.ipynb --to slides --post serve --template output_toggle.tpl
```

To run the corresponding notebook with examples, use

```bash
jupyter notebook graph-examples.ipynb
```
