# Qfold
The Qfold executable can be found inside the QFOLD.zip. Here are the steps for reproduction:
1. Unzip to a folder you can find and copy the address of the folder (Ctrl-c)
2. Open a Command Prompt window and type “cd” then right-click and choose Paste to paste in the address of the folder 
3. Pick the .ct file for an RNA sequence (recommended less than ~500 nt, e.g. ASE_00001.ct. Note that .ct files can be obtained from the RNA strand database
4. Type “Qfold ASE_00001.ct”. Note that the program takes only one input argument which is the .ct filename
5. The program is set to run for 1 minute. The output files have prefixes solver_QUBO and stat_ and list the progression of solutions.

Dependencies:
1. The current version of software is only tested on Windows 7.
2. Some of the Qfold output related to MFE calculation depends on RNAeval executable from ViennaRNA services. The program assumes that the executable is installed 
   and found under the Windows Path variable.

