# Approach:

* We try a brute force for approach on a  minimal subset of input  (n bits) to see if we can identify in the output some good outcome returning valid english words. 

* We write a function to convert hex to bits

* We write a function to generate all the possible masks of length n

* making XOR between  two ciphertexts  allow us to (by neutralizing the key) tell which bits are equal and which one are different among the input strings.
