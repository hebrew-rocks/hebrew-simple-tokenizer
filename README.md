## A robust Hebrew tokenizer

Splits a chunk of Hebrew text into space tokens.

   python hebtokenizer.py < input > output
   

default encoding is utf8. can specify inpunt and output encodings with the --ie and --oe switches, respectively:

   python hebtokenizer.py --ie cp1255 --oe utf16 < input > output
   

requires python 2.5 or above (python3 not supported) 
