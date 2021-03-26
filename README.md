# Grover-Algorithm
Quantum algorithm application on a classical machine. Grover's algorithm is a search and find solution returning the highest probable match in an unsorted domain.

## Authors:<br />
DK Lee, Derek Dang

## Class:<br />
``GroverAlgorithm.java``

## Purpose:<br />
Search a database for an element. Returns a probability of that element.

## Compile:<br />
``javac Driver.java``

## Run:<br />
``java Driver``

## Input:<br />
numQubits - the number of qubits passing in the top wire.<br />
value - the special value to be found.

## Output:<br />
The probability of finding the passed in value.

## Notes:<br />
1) To search for a term, enter in the decimal value. The program calculates the probability using decimal values.<br />
2) Reminder that this is a classical program running a quantum program. Running time of this program is O(2^n), but the quantum version is ``O(√(2^n))``, which is quadratic speedup.
