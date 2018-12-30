# latex-macro-collection

## Installing the library in your local environment


The easiest way to install package files is to place them on your TeX search path. To find your default location use kpsewhich (included with TexLive).

1) Create a default directory on your TeX search path:

```shell
$ kpsewhich -var-value=TEXMFHOME
/home/USER/texmf
```

2) Create a tex/latex directory in this location:

```shell
$ cd `kpsewhich -var-value=TEXMFHOME`
/home/USER/texmf$ mkdir tex
/home/USER/texmf$ mkdir tex/latex
```

3) Change to the new tex/latex directory

    /home/USER/texmf/tex/latex$ cd tex/latex
	
4) Use git to clone the repository

    /home/USER/texmf/tex/latex$ git clone https://github.com/dsenften/latex-macro-collection.git
	
5) Check to see if gitdags.sty (one of the modules) can be seen by TeX	

    $ kpsewhich xcolor-solarized.sty	
