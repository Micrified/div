# div
Div is a very simple C program that generates a comment banner given an input line thorugh `stdin`. The banner width is adjustable, though set to 80 characters by default. 

### Installation
Div is meant to be used with acme, so for this program to be useful you'll want to install that first. I've got acme installed as part of plan9ports, a port of several plan9 programs to other architectures. Once you have acme available, using `div` is trivial: 

1. Compile `div.c` to an executable named `div`. 
2. Install the binary somewhere on your path (e.g. `/usr/local/bin`).

### Usage

Div supports just one [optional] argument, that being the length of the comment banner. 

* `div [length]`

To use the program in acme, simply add a tag to your window. For instance, providing you're okay with just the 80-character standard with. You could write `|div` as a tag. Otherwise specify the length (e.g. `|div 120`). 

To produce the banner, highlight a portion of text that you want to be shown in the title with mouse button 1 (left mouse button). Then middle-click (mouse button 2) on the tag to overwrite it with the output of `div`. 

### Misc

The title text is automatically centered by default, and is restricted to one line. If the text exceeds the maximum line length, it is cut short in order to fit.
