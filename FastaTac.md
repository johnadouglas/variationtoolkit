


## Download ##
Download the sources from Google-Code using [subversion:...](http://subversion.apache.org/).
```
svn checkout http://variationtoolkit.googlecode.com/svn/trunk/ variationtoolkit-read-only
```
... or update the sources of an existing installation...
```
cd variationtoolkit
svn update
```
... and edit the `variationtoolkit/congig.mk` file.

## Example ##



```

$ fastaslice -e 50 -L 50 < rotavirus.fasta  | fastatac  | head

>gi|14662886|slice:250-275
TTTGTAACCGGCCCCCCTTAAAACT
>gi|14662886|slice:200-250
CATCATTTCATACCATCATATCGGCATCAATCAAAATGGTCCCATGACTT
>gi|14662886|slice:150-200
CCTATTCCGCGCTCAGGTATATCTTTTCAACCCATCAATATTGCAGCCTT
>gi|14662886|slice:100-150
CAGGTTGCCCTTCTCTCAGCGCCAGTTACAGGCCCATTTCCCAGTCAAGT
>gi|14662886|slice:50-100
CACTCCTTTCACAAATCCCGAATTCTCTATCTAACTAACATTTGGCATAT

```




