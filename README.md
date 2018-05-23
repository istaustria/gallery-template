# Gallery Template

An image template for items of the hallway gallery at the Visual Computing Groups at IST Austria.

## Getting Started

### Installing

Create a local copy of the project from its Git repository by executing
```
git clone git@github.com:istaustria/gallery-template.git
```
inside the desired project directory.
Alternatively, one can directly download the repository content.

### Testing

The main element of the template is its LaTeX file `template.tex`.
In order to ensure that it is working correctly, execute
```
pdflatex template.tex
```
in the console or - preferably - use your standard LaTeX editor.

Based on the provided test image ```image.jpg``` (and the text in `template.tex`), a full gallery item is created as `template.pdf`.
This item should exactly match the provided reference `template-reference.pdf`.
If this is not the case, update your LaTeX distribution and all its packages.

## Usage

To adapt the template to your gallery item, you should directly edit `template.tex`.
It contains ample comments and documentation for all its functionality.

The main steps would be:

1. Either replace `image.jpg` with your image or alter all occurrences of `{image}` in `template.tex` to the filename (without extension) of your image file.
2. Choose the color values for the background, the text box, and the text (or set the opacities to zero for transparent items).
3. Choose a placement of your image on the gallery item (i.e., centered, left, or right).
4. Edit the text of the text box to reflect the title, authors, affiliations, venue, and abstract of your work.

## Development

This is a living document and you are encouraged to contribute to its functionality and robustness.

> **In case you add personal improvement or fix bugs, please commit them to the repository!**

## Contributors

Developed by Thomas AUZINGER [<thomas.auzinger@ist.ac.at>](mailto:thomas.auzinger@ist.ac.at) (see [personal webpage](http://auzinger.name)).

## License

Copyright 2018 Thomas AUZINGER [<thomas.auzinger@ist.ac.at>](mailto:thomas.auzinger@ist.ac.at)

This software uses the MIT License.
See LICENSE.txt.
