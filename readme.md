# The h5bp ant build script merged back into HTML5 boilerplate

The build script is a tool that optimizes your code for production use on the web.

## I just moved it back ...

The build script h5bp-ant-bs git://github.com/h5bp/ant-build-script.git has now been split out from the HTML5 boilerplate git, the build script(s) from the main h5bp repo, as I wanted to save some time when building new projects by just using createproject.sh I moved it back into the current HTML5 boilerplate.

In addtion I updated the usage functionality so that you no longer have to specify a new project on the command line, but can specify it after you run creatproject.sh which accords with the original usage functional specification (and follows the current instructional build video *see main project website).

HTML5 boilerplate project work can be found here;

github: https://github.com/h5bp/html5-boilerplate

the main project page is here;

http://html5boilerplate.com/

I will be updating this git when and if required to suit my own evil projects, I strongly suggest getting involved in the HTML5 boilerplate project which I hope to do at some future point, and not following this git.


## Acknowledgements

This git has been brought to you by the HTML5 boilerplate project team here https://github.com/h5bp/html5-boilerplate and here http://html5boilerplate.com/.


## Requirements

Out of the box, the build script requires Java 1.6. 

Ant itself requires the Java JDK, version 1.4 or later. 1.5 or later is strongly recommended. 

Closure Compiler, our tool for script minification, requires Java 1.6. 

This means that OS X versions prior to 10.6 are no longer supported out of the box. 
[SoyLatte][soylatte] provides 10.4 and 10.5 builds of OpenJDK 7 for Intel OS X machines. However, only OS X 10.5 builds of OpenJDK 7 are available for PowerPC based Macs due to a bug in the 10.4 Compiler.  
( Be sure to read the Download link as the archives are password protected "to provide a click though agreement" of the JDK licensing. )

[soylatte]: http://landonf.bikemonkey.org/static/soylatte/ 

Alternatively, YUI Compressor, which requires Java > 1.4, could be swapped out for Closure Compiler.
