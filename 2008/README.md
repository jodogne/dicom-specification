```
$ seq -f 'ftp://medical.nema.org/medical/dicom/2008/08_%02gpu.pdf' 0 20 | xargs -n1 wget
```
