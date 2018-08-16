STA521 Fall 18
===========

Course materials for STA 521 - Fall 2018 semester at Duke University.

Course website is at https://stat.duke.edu/courses/Fall18/sta521/.



The repository website contains code for the STA521 website
that is compiled using jekyll.  The colors are changed in the file noita/foundation/css/foundation.min.css
(use firebug to see colors and then edit file to add new ones;
colorpicker is a good way to find the HEX for colors)

Current colors (from Pantone Spring 17)
* 5587A2 (Niagara) for links and
* 0C4C8A (Lapis Blue) for Headers, info at top etc
* 97D5E0 (Island Paridise) for hover link 


The other directories include materials for lectures (LaTeX, R, data)


### Using this as a template for a new course

The file _noita/default.html has the "title" for the website that
appears in browsers and needs to be updated if this is to be 
used as a template for a new course

The file _config.yml has the course number, header and year and
controls the top menu bar

The file Makefile has the directory for the remote static site and
needs to be updated before issuing make push.

_This web design is cloned and modifed from Mine Cetinkaya-Rundel's
material for STA 101 at
https://github.com/mine-cetinkaya-rundel/sta101_sp15 using the noita theme._


