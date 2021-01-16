# Di-Finder
C# tools for Dinucleotide Short Tandem Repeat (STR) Finder Base ensembl 
How does Di-nucleotide Tandem Repeats Finder work?
In order to find small repeating sequences in a large sequence, a repeating loop was designed equal to the length of the large sequence
 Inside this loop, all consecutive di-nucleotides are examined and their list is extracted. This process is checked by a regular expression algorithm. 
A regular expression is a sequence of characters that defines a search pattern. These patterns are usually used by sequence search algorithms to "find" operations on sequences.
This is a technique used in computer science, especially in formal language theory. 

This process is repeated for the length of the sequence for each nucleotide pair and the implemented algorithm does not support any mismatch 
because we are looking for sequences that have not changed over time and have remained stable.

 
