# TYPO3 Boilerplate

The TYPO3 Boilerplate is inspired by the HTML5 Boilerplate.

It contains all standard files to create a new project and could be use instead
of the TYPO3 dummy package.

## How to use

### Optional SASS integration

If you want to use SASS, you will find all needed files in a special SASS folder
(/fileadmin/styles/sitename(css/sass). The main SASS file style.scss contains a
predefined set of variables (different colors and font sizes used in
_content.scss) and includes additional files  
More information about how to use SASS: "SASS Tutorial":
http://sass-lang.com/tutorial.html

The best way to create the final style.css file is to watch the whole SASS
directory:
Use the terminal and navigate to your templates folder
(here /fileadmin/styles/sitename/).
Than use:
*sass --watch css/sass:css*

This command will write a complete style.css file in your css directory by
including all other SASS files. Keep in mind, that you have to reset the image
paths from ../../images/mypic.jpg to ../images/mypic.jpg in your SASS files,
because they are not imported with @import like the normal YAML way did.

## Versions

* HTML5 boilerplate 4.3.0
* jQuery 1.11.0
