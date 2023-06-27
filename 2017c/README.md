```
$ seq -f 'http://dicom.nema.org/medical/dicom/2017c/output/pdf/part%02g.pdf' 0 25 | xargs -n1 wget
$ wget http://dicom.nema.org/medical/dicom/2017c/source/docbook/part15/part15.xml
```
