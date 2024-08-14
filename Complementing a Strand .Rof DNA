#Problem
In DNA strings, symbols 'A' and 'T' are complements of each other, as are 'C' and 'G'.

The reverse complement of a DNA string s is the string sc formed by reversing the symbols of s, then taking the complement of each symbol (e.g., the reverse complement of "GTCA" is "TGAC").

Given: A DNA string s of length at most 1000 bp.

Return: The reverse complement sc of s.

# Answer(Lazy solution)
seq_rev <- readLines("~/Desktop/rosalind_revc (2).txt")
seq_rev <- stringi::stri_reverse(seq_rev)
seq_rev <- gsub(x = seq_rev,pattern = "A",replacement = "t",)
seq_rev <- gsub(x = seq_rev,pattern = "T",replacement = "a",)
seq_rev <- gsub(x = seq_rev,pattern = "C",replacement = "g",)
seq_rev <- gsub(x = seq_rev,pattern = "G",replacement = "c",)

seq_rev <- gsub(x = seq_rev,pattern = "a",replacement = "A",)
seq_rev <- gsub(x = seq_rev,pattern = "t",replacement = "T",)
seq_rev <- gsub(x = seq_rev,pattern = "c",replacement = "C",)
seq_rev <- gsub(x = seq_rev,pattern = "g",replacement = "G",)
