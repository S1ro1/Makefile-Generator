

# A simple makefile generator

## Download

```console
$ wget https://raw.githubusercontent.com/S1ro1/Makefile-Generator/master/makefile_gen
$ cat makefile_gen >> .bashrc && rm makefile_gen
```

## Usage

#### To use this generator, simply write generate into your shell and specify options

* -h: Prints help
* -c [OPTION]: sets compiler to a specified option, default is gcc
* -* [OPTIONS]: sets compiler flags to specified options, default are '-std=c99 -Wall -Wextra'
* -t [OPTION]: sets the target name for the executable to be created

```console
$ generate -c gcc -Wall -Werror -Wextra -t target_name 
```
