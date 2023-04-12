## Lung cancer prediction

## Description
This respository contains the steps in the development of a machine learning model that clusters different types of histology tags of lung cancer.

## Data
The clinical dataset can be downloaded here: https://wiki.cancerimagingarchive.net/download/attachments/16056856/Lung3.metadata.xls?version=1&modificationDate=1404237338168&api=v2. While the gene expression dataset can be found at https://ftp.ncbi.nlm.nih.gov/geo/series/GSE58nnn/GSE58661/matrix/GSE58661_series_matrix.txt.gz. The labels for the gene expression data were gotten from the clinical dataset.

## Installation
Single install
The easiest way to install all the required packages is via conda. How to install conda on your system can be found here.

Multiple installs
An other option is to install each package seperately, either with conda or pip.

conda:

  conda install <PACKAGE>=<VERSION>
pip

  pip install <PACKAGE>==<VERSION>
NOTE: make sure to use the correct versions, which are listed here.

Getting started
To open the dashboard run the dashboard_mosquitoes.ipynb notebook from top to bottom.

## Requirements
| Software | Version |
| --- | --- |
| Python |	3.9.7 |

## Packages
| Package | Version |
| --- | --- |
| numpy	| 1.21.2 |
|pandas	| 1.3.3 |
| bokeh	| 2.3.3 |
| panel	| 0.12.1 |
| holoviews |	1.14.6 |
| hvplot |	0.7.3 |
|scipy |	1.7.1 |
| jupyter |	1.0.0 |
|statsmodel |	0.12.2 |
| pathlib	| 1.0.1 |

## License
This project contains an MIT license.

## Legal
This study is based on a preexisting HIPAA compliant dataset that contains no personally identifiable information. Due to the deidentified nature of the datasets obtained; this study was not considered human subjects research nor required consent per the Helsinki Declaration and was therefore exempt from VCU Institutional Review Board review.
