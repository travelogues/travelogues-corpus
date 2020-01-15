# Travelogues Corpus

A corpus of German language travelogues from the period 1500-1876, drawn from the 
[Austrian Books Online project](https://www.onb.ac.at/digitale-bibliothek-kataloge/austrian-books-online-abo)
of the [Austrian National Library](https://www.onb.ac.at/). The corpus was compiled by the domain experts
of the [Travelogues Project](https://travelogues-project.info), using the [SACHA](http://iiif.onb.ac.at). Texts 
are the result of Optical Character Recognition (OCR), and were not manually corrected. Travelogues is funded through 
grant I 3795 of the Austrian Science Fund (FWF), and grant 398697847 of the German Research Foundation
(DFG).

<br/>

## Repository Contents

``` 
- 16th_century
  |- 16c-books.zip (14 MB, 66 files)
  |- 16c-metadata.zip (68 KB, 66 files)
- 17th_century
  |- 17c-books.zip (49 MB, 204 files)
  |- 17c-metadata.zip (202 KB, 204 files)
- 18th_century
  |- 18c-books.zip (214 MB, 949 files)
  |- 18c-metadata.zip (814 KB, 949 files)
```

__IMPORTANT! [Git LFS](https://git-lfs.github.com/) must be installed on your system in order to clone this repository correctly.__

<br/>

## Accessing Digital Objects Online

Book and metadata files are named according to their barcode identifiers in the Austrian
National Library. The permanent URLs to the digital objects can be constructed by prefixing 
the barcode with `http://data.onb.ac.at/ABO/+`, e.g. for barcode `Z180627808`:
[http://data.onb.ac.at/ABO/+Z180627808](http://data.onb.ac.at/ABO/+Z180627808).

<br/>

## Use of the Corpus for Machine Learning

This corpus was used to train an automatic classifier in this publication:

> Jan Rörden, Doris Gruber, Martin Krickl, Bernhard Haslhofer (2019) 
> Identifying Historical Travelogues in Large Text Corpora Using Machine 
> Learning (accepted for publication), [arXiv:2001.01673](https://arxiv.org/abs/2001.01673) [cs.DL] 

More information and source code is available in this repository: [Travelogues/identifying-travelogues](https://github.com/Travelogues/identifying-travelogues).

<br/>

## License

- Text files: no copyright - non commercial use only [NoC-NC 1.0](https://rightsstatements.org/page/NoC-NC/1.0/)
- Metadata: licensed under [Creative Commons CC0](https://creativecommons.org/share-your-work/public-domain/cc0/)





