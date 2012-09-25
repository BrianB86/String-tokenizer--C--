String-tokenizer--C--
=====================
This is a program thats takes in user input and tokenizes it based on the string of separators given to it.

example: ./tokenizer "abc" "aIbLovecGit" - token:I
                                           token:Love
                                           token:Git
                                           
This was my first C program I made besides hello world and other simple programs. I do not use strtok or strsep to help--
me tokenize the string.
I do use strpbrk to locate a separator and then do pointer arithmatic to get the token from the token string.
This program improved my understanding of how pointers work as well as malloc and free.