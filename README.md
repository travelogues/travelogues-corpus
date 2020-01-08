# Travelogues Corpus

A corpus of German language travelogues from the period 1500-1876, drawn from the 
[Austrian Books Online project](https://www.onb.ac.at/digitale-bibliothek-kataloge/austrian-books-online-abo)
of the [Austrian National Library](https://www.onb.ac.at/), compiled by the domain experts
of the [Travelogues Project](https://travelogues-project.info). The texts are the result of
Optical Character Recognition (OCR), and were not manually corrected. Travelogues is funded through 
grant I 3795 of the Austrian Science Fund (FWF), and grant 398697847 of the German Research Foundation
(DFG).

## Repository Contents

``` 
- 16th_century
  |- books
  |  |- 16c-non-travelogues.zip (7.6 MB, 67 files)
  |  |- 16c-travelogues.zip (14 MB, 66 files)
  |- metadata
  |  |- 16c-metadata-zip (130 KB, 133 files)
  |
- 17th_century
  |- books
  |  |- 17c-non-travelogues.zip (47 MB, 162 files)
  |  |- 17c-travelogues.zip (49 MB, 204 files)
  |- metadata
  |  |- 17c-metadata-zip (348 KB, 366 files)
  |
- 18th_century
  |- books
  |  |- 18c-non-travelogues.zip (190 MB, 784 files)
  |  |- 18c-travelogues.zip (214 MB, 949 files)
  |- metadata
     |- 18c-metadata-zip (1.5 MB, 1733 files)
```

__IMPORTANT! [Git LFS](https://git-lfs.github.com/) must be installed on your system in order to clone this repository correctly.__

## Accessing Digital Objects Online

Book and metadata files are named according to their barcode identifiers in the Austrian
National Library. The permanent URLs to the digital objects can be constructed by prefixing 
the barcode with `http://data.onb.ac.at/ABO/+`, e.g. for barcode `Z180627808`:
[http://data.onb.ac.at/ABO/+Z180627808](http://data.onb.ac.at/ABO/+Z180627808).


## Why Travelogues and Non-Travelogues?

The books are subdivided into __travelogues__ and __non-travelogues__. Non-travelogues were
used as counter-examples for training an automatic classifier in the publication

```
...accepted for publication... 
```

More information and source code is available in this repository: [Travelogues/identifying-travelogues](https://github.com/Travelogues/identifying-travelogues).

## License

- Text files: no copyright - non commercial use only [NoC-NC 1.0](https://rightsstatements.org/page/NoC-NC/1.0/)
- Metadata: licensed under [Creative Commons CC0](https://creativecommons.org/share-your-work/public-domain/cc0/)





