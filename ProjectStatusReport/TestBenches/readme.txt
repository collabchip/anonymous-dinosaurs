TestBenches
~~~~
Deliverables:

* Test Vectors Generator (!!) :

We implemented an extensive testbenching procedure. A simple C script was created for .txt files to be automatically generated. For a given number of inputs, all these possible input vectors were given as arguments to a 'generator' System Verilog file. This file was per case the behavioral implementation of the module (logic equations). The outputs were stored as an additional .txt file. Both the input and output vectors were given as argument to the Verilog Deck generated using Electic. We were cycling through all these possible cases, checking that all outputs and inputs match the expected values every single time. 

For instance, it is noteworthy that the Partial Product Generator was tested under all the different possible test cases (over 1 million cases with no error messages)!!

* TestBenches : Verilog Files + PrintScreens + I/O vectors .txt files

All the generated Verilog Decks and the used System Verilog Testbenches are provided. Note that not all the input/output vectors .txt files are uploaded given the GitHub's upper limit of file size (some text files were bigger than 100MB!!).

