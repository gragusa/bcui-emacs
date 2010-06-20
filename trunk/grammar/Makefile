#
# File: grammar/Makefile
#
# $Id$
#

INCDIRS = -I. -I/usr/local/include/link-grammar

objects := grammar.o

all: $(objects)
	g++ -g -llink-grammar -o grammar $(objects)

grammar.o: grammar.cc
	g++ -g $(INCDIRS) -c grammar.cc
