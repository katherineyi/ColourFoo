# ColourFoo <Work-In-Progress>

This is a programm written in C.

Fucntions: This program will take an image and produce the two most dominate colors in the image.

Steps:

1. Use malloc() to store the image as variable
2. Make sure to allocate memory to do:
   1. store image as variable
   2. checking if we have enough memory
   3. dont' forget about the variable (assigned memory), and don't have memory leak
   4. Hash table, each rgb  combo,  
   5. Build the data structure yourself, functions to go with it, safe way to access the hash table. The first parameter is the pointer to memory.
   6. Normalize the shades into one category. —> bonus for normalization 
   7. Memory management!! Use Malloc to ask for memory!!
3. Caculation on the color variable (hashtable? array?)
4. Print out the 2 most dominate colors