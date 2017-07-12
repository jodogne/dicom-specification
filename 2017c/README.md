```
$ seq -f 'http://dicom.nema.org/medical/dicom/2017c/output/pdf/part%02g.pdf' 0 25 | xargs -n1 wget
```
