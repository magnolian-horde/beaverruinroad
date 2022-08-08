Beaver Ruin Road
================

_Beaver Ruin Road_ is a short fantasy adventure for [Old-School Essentials][OSE]
where three to five first-level adventurers traipse along a river to uncover
what diverted its course and flooded the villa of Basendal.

[OSE]: https://necroticgnome.com/collections/rules

Getting Started
---------------

This adventure is written in [ConTeXt] so any TeX or LaTeX users
should pay attention that this is done differently.
To compile the book, you will need a **full** [TeX Live] installation
where _all_ the necessary packages and then some are installed.

[TeX Live]: https://tug.org/texlive/
[ConTeXt]: https://wiki.contextgarden.net

Once you have that, run:

```shell
arara beaverruinroad.tex
```

If [Arara] is not installed, try running:

```shell
tlmgr install arara
```

Superuser privileges (`sudo`, `doas`, `su`) may be required.

[Arara]: https://islandoftex.gitlab.io/arara/

From then on, you should be able to read `beaverruinroad.pdf` with any
PDF viewer available.
Windows folk, I would recommend [Sumatra PDF](https://www.sumatrapdfreader.org/free-pdf-reader)
for that role.
MacOS and most GNU/Linux distributions should have their own viewer
preïnstalled on their systems.
