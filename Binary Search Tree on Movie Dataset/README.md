A sample execution of the program will be as follows:

`./runMovies arg1 arg2 arg3`

`arg1` is a boolean flag, which can be `true` or `false`; `arg2` represents the input file containing movies and ratings (as described before); `arg3` is either the starting letters of a movie name (movie prefix) or a number

## Part 1: Find the highest rated movie that starts with a given prefix
If `arg1` is `true`, then `arg3` should be a movie prefix. In this case, the program will print the pre-order traversal of the tree to stdout, for each node visited, output the movie name, rating, and depth. Then the program will print the movie with the highest rating beginning with the prefix was passed in as `arg3`.

## Part 2: Analyze the time to search and insert keys in a BST and write a report
If the `arg1` is `false`, then the program will collect timing data for the report. 
