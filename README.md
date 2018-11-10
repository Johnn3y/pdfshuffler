# About

*pdfarranger* is a small python-gtk application, which helps the user to merge
or split pdf documents and rotate, crop and rearrange their pages using an
interactive and intuitive graphical interface. It is a frontend for
python-pyPdf.

*pdfarranger* is a fork of Konstantinos Poulios's pdfshuffler
(see [Savannah](https://savannah.nongnu.org/projects/pdfshuffler) or
[Sourceforge](http://sourceforge.net/projects/pdfshuffler)).
It's an humble tentative de make the project a bit more active.


# Install

In order to install run:

On Debian based distributions:

```
sudo apt-get install gettext python3-wheel python3-gi python3-gi-cairo gir1.2-gtk-3.0 gir1.2-poppler-0.18
```

On Arch Linux:

```
sudo pacman -S poppler-glib gettext python-pip python-gobject gtk3 python-cairo
```

Then:

```
pip install --user -r https://raw.githubusercontent.com/jeromerobert/pdfarranger/master/requirements.txt
```
