# Build nemo 4.0 beta

Juha Lento, CSC, 2018-11-15

## Status

On going...

- xios-2.5 builds and install on sisu.csc.fi with GNU compilers

## Dowload sources

```bash
svn co ​http://forge.ipsl.jussieu.fr/ioserver/svn/XIOS/branchs/xios-2.5
svn co http://forge.ipsl.jussieu.fr/nemo/svn/NEMO/trunk
git clone https://github.com/jlento/nemo.git
```

## Build

The build commands for different compilers and machines are in files
`build-<compiler>-<host>.sh`. The build instructions for xios-2.5 dependency are
in subdirectory xios/2.5, if the library is not already available.
