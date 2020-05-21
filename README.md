# Noraim_Nunez_21May2020_Redo

1. This is starting to bring together a number of aspects of programming. In Assignment 2, you were tasked with writing a program that calculated the {sum, mean, and RMS} for a list of numbers. In this question, the goal is to take that code and reuse it but making it more user friendly, while also practicing with using functions. As such, your task is to write a program that does the following :
  A. Takes a single command line argument which is the path to a plain text file which is itself a newline delimited list of numbers. An example of such a file is provided attached to the course website and also typed below. The name of the file is assignment3 newline numbers.txt.
  
  B.Read in this text file to a vector of float values (std::vector<float>). You will have to do some casting of values from the type that is read in and the float type.
  
  C. Define and use three functions to calculate the {sum, mean, and RMS} which take as an argument the vector of numbers that you have defined and return the value of their calculation, a single float.
  
  D. Print the results to the screen in an orderly manner with a description of the value that is being printed. 
  
  2. Describe what is happening in each of the steps of assignment to the array numbers. The goal is to make a prediction of what the values of each of the entries in the array will be prior to executing the code. After making this prediction, compile and execute the code. Does your prediction agree with what you see? If not, debug your understanding to determine what was incorrect in your logic. Finally, execute the code multiple times in a row and confirm that you see the same values in the array each time. Include you printout of the code, either in the form of a screenshot or in your answer sheet.
  
  3. In this exercise, write a piece of code in which you do the following.
    A. Define a class that represents a four-vector. Call this class FourVector.
    B. Constructor : Should be implemented to force the user to initialize the members of the class
    C. Class Members : This should contain fundamental memory types that represent the energy and three- momentum (px,py,pz) of a given particle. Do not use a vector to represent energy or momentum. Call these members E, Px, Py, and Pz. 

Class Method 1 : Should be called and replace the contents of the full four vector with the E, px, py, and pz that you specify as arguments. Call this function SetFourVector.

Class Method 2: Should be called and return the invariant mass of the four vector (as a float). Call this function GetMass.

Class Method 3: Should be called and return the pseudorapity (η : Greek “eta”) of the four vector (as a float). Call this function GetEta

Class Method 4: Should be called with one argument which is an instance of another four vector and calculate the difference in the azimuthal angle (∆φ) between the two three-momenta of these vectors. Make sure that you take into account that the largest angular distance between two three-vectors is π. Call this function DeltaPhi.

Class Method 5: Should be called with one argument that is another four vector and calculates the difference in the pseudorapity (η) of the two four-vectors. Call this function DeltaEta.


