#	Makefile for filterBam.cc and filterBam.tex
#	
# 	Created: 28-February-2012
#	Last modified: 15-October-2015

all: 
	(cd src;make CXX=$(BAMTOOLS_CXX) CC=$(BAMTOOLS_CC) BAMTOOLS=$(BAMTOOLS))

clean:
	(cd src; make clean; cd ../bin; rm -f filterBam; cd ../../../bin; rm -f filterBam)
