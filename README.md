# Dockerfile for delve

See [Delve_User_Manual.pdf](http://fantom.gsc.riken.jp/5/sstar/File:Delve_User_Manual.pdf) at FANTOM project for more details of delve.

Example:

```
docker run --rm -v "$(pwd)":/data -w /data inutano/delve delve index genome.fa
docker run --rm -v "$(pwd)":/data -w /data inutano/delve delve realign alignments.sam
```
