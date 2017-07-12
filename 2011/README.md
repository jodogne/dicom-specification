```
$ seq -f 'ftp://medical.nema.org/medical/dicom/2011/11_%02gpu.pdf' 0 25 | xargs -n1 wget
```
