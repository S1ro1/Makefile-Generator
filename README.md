

# A simple makefile generator

## Download

```console
$ wget https://raw.githubusercontent.com/S1ro1/Makefile-Generator/master/makefile_gen
$ cat makefile_gen >> .bashrc && rm makefile_gen
```

## Usage

### To use this generator, simply write generate into you shell and specify options

* -h: Prints help
* -c [OPTION]: sets compiler to a specified option, default is gcc
* -p [OPTION]: sets language to a specified option, supported options are 'c' and 'cpp'
* -* [OPTIONS]: sets compiler flags to specified options, default are '-std=c99 -Wall -Wextra'
* [FILENAME]: name of the file you wish to create makefile for

```console
$ generate -c gcc -p c -Wall -Werror -Wextra -Pedantic random_file_name
```