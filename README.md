# div
Div is a very simple C program that generates a comment banner given a line in stdin. The banner width is variabble, though set to 80 characters by default. 

### Usage

Div is meant to be used with acme. I've got acme installed as part of plan9ports, which is a port of several pplan9 programs to other architectures. All you need to do to use this program within Acme is install it on your path somewhere (I installed the binary in /usr/local/bin) and then invoke it from within acme. 

To do that, just highlight whatever text you want to be in the comment banner with mouse button 1 (left-click), then middle click on a tag `|div`. This should replace your text with the comment banner version. 

To adjust the banner size, provide the tag/program with an argument representing the number of characters t long it should be. The title will be automatically centered within it. 
