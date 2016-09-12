# swingapis

## Set up the GitHub Pages

* Go to the organization page, https://github.com/minkonet.
* Create a repository, *swingapis*.
* Create a branch, *gh-pages*.
* Push the manual to the branch.
* Open https://minkonet.github.io/swingapis to see what has been published.

## Generate a manual

*Doxygen* is used to generate the manual.

### Doxyfile configuration

* For multiple input directory, set them in the _Expert tab > Input > INPUT_ of Doxygen GUI frontend.
* To set the HTML output directory to the project root not to the html/, set '.' in the _Expert tab > HTML > HTML_OUTPUT_.
* To edit the main page, _mainpage.md_ is added. See the following doxygen configuration items.
** _Expert tab > Input > Input_
** _Expert tab > Input > USE_MDFILE_AS_MAINPAGE_
