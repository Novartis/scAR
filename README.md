
<p align="left">
  <img src="docs/_static/scAR_logo_white.png" width="250" title="scAR">
</p>

   
   
[![scAR](https://anaconda.org/bioconda/scar/badges/version.svg)](https://anaconda.org/bioconda/scar)
[![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/scar/README.html)
[![code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)
[![Documentation Status](https://readthedocs.org/projects/scar-tutorials/badge/?version=latest)](https://scar-tutorials.readthedocs.io/en/latest/?badge=latest)
[![semantic-release: angular](https://img.shields.io/badge/semantic--release-angular-e10079?logo=semantic-release)](https://github.com/semantic-release/semantic-release)
[![test](https://github.com/Novartis/scAR/actions/workflows/python-conda-build.yaml/badge.svg)](https://github.com/Novartis/scAR/actions/workflows/python-conda-build.yaml)
[![Stars](https://img.shields.io/github/stars/Novartis/scar?logo=GitHub&color=red)](https://github.com/Novartis/scAR)
[![Downloads](https://anaconda.org/bioconda/scar/badges/downloads.svg)](https://anaconda.org/bioconda/scar/files)

**scAR** (<u>s</u>ingle-<u>c</u>ell <u>A</u>mbient <u>R</u>emover) is a tool designed for denoising ambient signals in droplet-based single-cell omics data. It can be employed for a wide range of applications, such as, **sgRNA assignment** in scCRISPRseq, **identity barcode assignment** in cell indexing, **protein denoising** in CITE-seq, **mRNA denoising** in scRNAseq, and **ATAC signal denoising** in scATACseq, among others.

# Table of Contents

- [Installation](#Installation)
- [Dependencies](#Dependencies)
- [Resources](#Resources)
- [License](#License)
- [Reference](#Reference)

## [Installation](https://scar-tutorials.readthedocs.io/en/latest/Installation.html)
## Dependencies

[![PyTorch 1.8](https://img.shields.io/badge/PyTorch-1.8.0-greeen.svg)](https://pytorch.org/)
[![Python 3.8.6](https://img.shields.io/badge/python-3.8.6-blue.svg)](https://www.python.org/)
[![torchvision 0.9.0](https://img.shields.io/badge/torchvision-0.9.0-red.svg)](https://pytorch.org/vision/stable/index.html)
[![tqdm 4.62.3](https://img.shields.io/badge/tqdm-4.62.3-orange.svg)](https://github.com/tqdm/tqdm)
[![scikit-learn 1.0.1](https://img.shields.io/badge/scikit_learn-1.0.1-green.svg)](https://scikit-learn.org/)

## Resources

- Installation, Usages and Tutorials can be found in the [documentation](https://scar-tutorials.readthedocs.io/en/latest/).
- If you'd like to contribute, please read [contributing guidelines](https://github.com/Novartis/scAR/blob/main/.github/CONTRIBUTING.md).
- Please use the [issues](https://github.com/Novartis/scAR/issues) to submit bug reports.

## License

This project is licensed under the terms of [License](docs/License.rst).  
Copyright 2022 Novartis International AG.

## Reference

If you use scAR in your research, please consider citing our [manuscript](https://doi.org/10.1101/2022.01.14.476312),

```
@article {Sheng2022.01.14.476312,
	author = {Sheng, Caibin and Lopes, Rui and Li, Gang and Schuierer, Sven and Waldt, Annick and Cuttat, Rachel and Dimitrieva, Slavica and Kauffmann, Audrey and Durand, Eric and Galli, Giorgio G and Roma, Guglielmo and de Weck, Antoine},
	title = {Probabilistic modeling of ambient noise in single-cell omics data},
	elocation-id = {2022.01.14.476312},
	year = {2022},
	doi = {10.1101/2022.01.14.476312},
	publisher = {Cold Spring Harbor Laboratory},
	URL = {https://www.biorxiv.org/content/early/2022/01/14/2022.01.14.476312},
	eprint = {https://www.biorxiv.org/content/early/2022/01/14/2022.01.14.476312.full.pdf},
	journal = {bioRxiv}
}
```
