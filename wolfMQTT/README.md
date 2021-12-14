# wolfMQTT Manual

This is a pandoc generated version of the wolfMQTT manual.

## Building Manual

#### Prerequisites

In Ubuntu run the following, this will be a large download/install:

```sh
sudo apt install pandoc texlive-full doxygen graphvis
```

You also need Doxybook2 installed which can be found at: <https://github.com/matusnovak/doxybook2>. Unfortunately there is no package for this. Installation instructions can be found at: <https://github.com/matusnovak/doxybook2#Install>

If Doxybook2 is installed in a non-standard path you can use the environment variable `DOXYBOOK_PATH` to set it.

#### Building

To build the PDF:

```sh
make pdf
```

To build the HTML:

```sh
make html
```

To build both:

```sh
make
```

To run an HTML server (HTML is built to a temporary area for this):

```sh
make serve
```