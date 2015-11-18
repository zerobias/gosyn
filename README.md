# Gosyn
Golang universal syntactic and lexical parser of programming language. Description syntax through XML, validation through XLST-scheme

Parse text file to the syntax tree.

Contains the following levels of language representation:

1.Symbol level

	Transform the text file into a sequence of characters

2.Lexical level

	Transforms sequence of characters into tokens and lexemes - recognized words of existing grammar categories

3.Syntax level

	Checks set of lexemes for compliance with existing rules and creates a syntax tree of recognized rules, 
	structures and tokens
  
Terms and rules are defined in the XML file lang.xml with a special syntax. The XSD schema file langSchema.xsd allows to check for correctness grammar file
