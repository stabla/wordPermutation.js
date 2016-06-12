# wordPermutation.js
Make a permutation with a word or an array of letter. (e.g : 'no' have 2 possibilites of permutation, no OR on).

## How it works ?

This is based on **Heap's algorithm**. (I invite you to check wikipedia's page about it : https://en.wikipedia.org/wiki/Heap%27s_algorithm )

We have 3 function: 
  * For Heap's algorithm, 
  * Another for split word if it's an array with just one word, 
  * Main function named *permute()* which call *heap()* and *wordSplitter()*. It take each letter of the heap returned array (called   
  heapArr) and make a new posibilities. At the end, we have all posibilities into 'permutedArr'
  If the array 'myArray' contain a word, we call wordSplitter() to split the word into an array with letters. *heap()* need an array with letter to do his work !

### Improvement ?
  Any advice to improve the code ? Pull a request, it only will be amazing !
  
  
