# eagerbib data: data repository for eagerbib
This repository contains some pre-collected packages of reference information that can be used by [eagerbib](https://github.com/zimmerrol/eagerbib) to update your BibTex bibliography.

# Packages
The packages offered here are always up to date and will be updated once per month.

## Machine Learning & Computer Vision (MLCV)
This package contains the bibliography information of the most popular machine learning and computer vision conferences.

### Included Venues
- AAAI
- AIStats
- ECCV
- CVPR
- ICCV
- ICLR
- ICML
- NeurIPS
- IJCAI
- COLT
- UAI
- ICRA

### Installation
After installing [eagerbib](https://github.com/zimmerrol/eagerbib), download and install this package by running the following command on your system
```bash
eagerbib-updater -b https://github.com/zimmerrol/eagerbib-data/raw/data/data/mlcv.tar.gz
```

To remove previous packages and only use the new one, append the `--replace-existing` flag to this command.