# About

Unofficial LaTeX package for the required **cover page** for work at the University of Stuttgart, Computer Science.

This package is a replacement for the old diplomtitel.sty

## Features

- utf8 
- options for all required text on the coverpage

## Usage Example

An example can be found in thesis.tex 

## Supported Options

This package supports the following options:

- language: Language used for all labels and text.
	- `language=german` will use german (default)
	- `language=english` will use english

- title: Title of work. Should be placed in curly braces:

	- `title={My thesis title}`
	- `title={My very long thesis title}`

- author: Author of work. Should be placed in curly braces. May contain more than one author seperated by commas:
	- `author={Peter Lustig}`
	- `author={Peter Lustig, Franz Josef, Vladimir Sixth}`

- type: Type of work. May be set to one of the following values or arbitrary text in curly braces:
	- `type=bachelor` will label your work as Bachelor's Thesis
	- `type=master` will label your work as Masters's Thesis
	- `type=diplom` will label your work as Diploma Thesis
	- `type=study` will label your work as Student Research Project
	- `type=projectinf` will label your work as Projekt-INF
	- `type={research project}` will label your work as research project
	
- institute: States for which institute you are doing this work. May be set to one of the following values or arbitrary text in curly braces:
	- `institute=iaas` will state Institute of Architecture of Application Systems
	- `institute=ipvs` will state Institute of Parallel and Distributed Systems
	- `institute=fmi` will state Institute of Formal Methods in Computer Science
	- `institute=iste` will state Institute of Software Technology
	- `institute=iti` will state Institute of Computer Architecture and Computer Engineering
	- `institute=iris` will state Institute of Computer-aided Product Development Systems
	- `institute=vis` will state Institute of Visualization and Interactive Systems
	- `institute=visus` will state Visualisation Research Center Stuttgart
	- `institute=fac` will state Faculty of Computer Science
	- `institute={Custom fictional institute\\ including address}` will state Custom fictional institute including address

- number: Running number of work. May contain arbitrary text. Should contain the number you got for your work.
	- `number=1234` will label your work to have number 1234

- course: Type of study. May be set to one of the following values or arbitrary text in curly braces:
	- `course=cs` will state that your course of study is Computer Science
	- `course=se` will state that your course of study is Software Engineering
	- `course=mcl` will state that your course of study is Master Computational Linguistics
	- `course=msv` will state that your course of study is Maschinelle Sprachverarbeitung
	- `course=bis` will state that your course of study is Business Information Systems
	- `course={Maschinelle Sprachverarbeitung}` will state that your course of study is Maschinelle Sprachverarbeitung

- examiner: Your examiner. 
	- `examiner={Prof.\ Dr.\ Hans Mustermann}`

- supervisor: Your supervisor.
	- `supervisor={Otto Normalverbraucher, M.Sc.}`

- startdate: Startdate of your work.
	- `startdate={2012/06/01}`

- enddate: Enddate of your work.	
	- `enddate={2012/12/01}`

- crk: CR-Classification codes of your work. May be seperated by commas:
	- `crk={A.1, A.2}`





