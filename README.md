# Grover-Algorithm
Application of a quantum algorithm on a classical computer. Grover's algorithm is a search and find solution returning the highest probable match in an unsorted domain.

Authors:	DK Lee, Derek Dang

Class: 		GroverAlgorithm.java

Purpose:	Search a database for an element. Returns a probability of that element.

Compile:	javac Driver.java

Run:		java Driver	

Input:		numQubits - the number of qubits passing in the top wire.
		value - the special value to be found.

Output:         The probability of finding the passed in value.

Notes:

1)      To search for a term, enter in the decimal value. The program
        calculates the probability using decimal values.

2)      Reminder that this is a classical program running a quantum
        program. Running time of this program is O(2^n), but the quantum
        version is O(√(2^n)), which is quadratic speedup.
