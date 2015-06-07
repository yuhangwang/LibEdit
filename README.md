# LibEdit
**Libedit: command line editor library that provides generic line editing, history, and tokenization functions**

This is an unofficial verbatim redistribution of the binary&source form of the Libedit library under its open source license (Berkeley-style license) terms (see the LICENSE file).

This redistribution is under the same license as the original.

Please visit the official website for more details: http://thrysoee.dk/editline

## Download
You can download the compiled binary files at the [release page](https://github.com/yuhangwang/LibEdit/releases).

## Compilation notes
### Compilation environment
* CentOS 6.6
* x86_64 architecture
* Compiler: gcc version 4.4.7 20120313 (Red Hat 4.4.7-11)

### Compilation steps
#### Version: 5.22.0 (2015)
```bash
wget http://thrysoee.dk/editline/libedit-20150325-3.1.tar.gz
tar xvf libedit-3.1
cd libedit-3.1
./Configure -des --Dprefix=/home/steven/install/libedit-3.1
make 
make test | tee QualityVerification.txt
make install
```

### Quality verification

See the "QualityVerification.txt" for the output of "make check".