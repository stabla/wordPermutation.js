# wordPermutation.js
Make a permutation with a word or an array of letter. (e.g : 'no' have 2 possibilites of permutation, 'no' OR 'on').

## How it works ?

This is based on **Heap's algorithm**. (I invite you to check wikipedia's page about it : https://en.wikipedia.org/wiki/Heap%27s_algorithm )

We have 3 function: 
  * *heap()* : Heap's algorithm 
  * *wordSplitter()* : Split word if array is a word (e.g ['hello']), because it's also can be an array of letters (e.g ['h','e','l','l','o'])
  * Main function named *permute()* which call *heap()* and *wordSplitter()*. It take each letter of the heap returned array (called heapArr) and make a new posibilities. At the end, we have all posibilities into 'permutedArr'
  If the array 'myArray' contain a word, we call wordSplitter() to split the word into an array with letters. *heap()* need an array with letter to do his work !

### Possibilities 
*We'll not using factorial in this code, but it's cool to know how many possibilities there's without calculating all existing combination.*

There existing `n!` possibilities, which is equivalent to `1 * 2 * 3 * . . . * ( n - 1 ) * n`.
Clearly, with a word of 4 letters, we will have 24 possibilities, because: `4! = 4 * 3 * 2 * 1 =  24`

Pretty astonishing when you see a word with 5 letters have 120 combination possible. I let you imagine a word with much more letters... 

(**Fun Fact ?** : *Your words possibilities will start with the same letter (or number) (n-1)! times. But it's only a conjecture from me, not verified !*)

### Improvement ?
  Any advice to improve the code ? Pull a request, it can only be more cool ! 
  
  
