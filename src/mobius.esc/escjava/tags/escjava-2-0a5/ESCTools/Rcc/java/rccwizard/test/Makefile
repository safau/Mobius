# Copyright 2000, 2001, Compaq Computer Corporation

all: runtest

class:
	echo "No .class files need to be built"

source:
	echo "No .java files need to be built"

runtest: 
	rtestall

clean: 
	-rm -rf test*/out test*/diff test*/outdir test*/houdini.out
	find . -name \*~ -exec rm {} \;
	find . -name \*.class -exec rm {} \;
	find . -name core -exec rm {} \;

