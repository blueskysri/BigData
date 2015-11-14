The Aim of the project is to Classify new incoming emails into ham and spam.
Used: Hadoop/MapReduce , python and java

Main Folder:
	Mapper1  -Mapper Class for the training
	Reducer1 -Reducer Class for the training
	Driver   -Driver Class which runs Mapper and Reducer with the inputs
	NB - Naiver Bayer class which Takes the new input and classifies into spam email or ham email.

Converter.py  - Used to convert the PST files to text files 
divide.py     - Used to seperate out test and traning set
Breakingtext.py - used to remove unwanted lines to test on Weka 
