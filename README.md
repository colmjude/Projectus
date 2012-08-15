# Projectus

Initial project setup. Includes basic directory structure and a naked style guide, with more to come (see TODO). I use it to help me out at the beginning of projects but feel free to fork, use and change.

## Credit
Reading this article (http://24ways.org/2011/front-end-style-guides) by Anna Debenham inspired me to think about putting one of these together.
Seeing and using Paul Robert Lloyd's Barebones project (https://github.com/paulrobertlloyd/barebones) encouraged me to finally put it together.

## Usage

### How to use the pattern primer

Requires node.js version 0.5.0+
You'll also need to install the connect node.js package. Do so by running:

    npm install connect

Add your project's CSS files to the head of the `source.html` file.
Add the script tags you wish to use for your project, in the order you require, to `scripts.html`.
Place all your HTML extracts into the `<root>/_patterns` folder. Navigate to the root directory of Pattern-Primer-on-Node and run: 
	
    node pattern-primer.js
	
You can then navigate to http://localhost:8080/ to see the output.

Alternatively, if you want to generate a 'standalone' version of the primer output, then you can also run the program with the `tofile` arg as follows:

    node pattern-primer.js --tofile


## TODO
* ~~change to work with normalize.css as its base CSS~~
* strip more of the element usage content, that can be added on a per project basis
* ~~add a pattern primer, going to use this node.js port (https://github.com/beardtwizzle/pattern-primer-on-node) of The Pattern Primer (<https://github.com/adactio/Pattern-Primer/>) by Jeremy Keith (<http://adactio.com/>)~~
* ~~tweak primer to go through js folder and add scripts to the bottom of the primer => ended up just using a script.html file so that dev can determine script load order~~
* ~~move basic layout styles of the primer out of patterns.css~~
