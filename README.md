# Overview

The purpose of the *Graphene* code is to compute the electronic structure of graphene nanomaterials using the Tight Binding approximation with a Hubbard term to account for electronic correlation. The code is able to onsider external electric and magnetic fields under mechanical strain.


# How it works

# How to use it

Clone this repository,

```console
$ git clone https://github.com/chinchay/Graphene.git
```

compile the executable, assuming Intel Fortran and the MKL library are installed on your machine.

```console
$ make
```

Alternatively, if Docker is installed and the daemon is running, type the following

```console
$ docker build -t containerName .
$ docker run -it --rm -p 8888:8888 -v $PWD/src:/work/src containerName
$ make
```


# Development Environment



# Useful Websites





# Future work


## References
        
* [Rocha, C. __*Propriedades Físicas de Nanotubos de Carbono*__. Universidade Federal Fluminense, Brazil, 2005](http://oldsite.if.uff.br/index.php?option=com_content&view=article&id=348)
* E. Economou. __*Green’s Functions in Quantum Physics*__. Springer, 2006. 11, 12, 70
* M. Di Ventra. __*Electrical Transport in Nanoscale Systems*__, 1st edition, pp 150. Cambridge University Press, 2008. 73


## Copyright and license

Code released under the MIT License