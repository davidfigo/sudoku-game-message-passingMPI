# ParallelSudoku

Parallel game using MPI of university Instituto Superior Técnico, Universidade de Lisboa (2017/2018).
It was developed a serial and parallel implementations of a sudoku solver.

### Description:
The puzzle consists of a partially filled
matrix n × n. The algorithm needs to fill the blank positions with values 1 through n
such that no number is repeated on each of the n rows, n columns, or the n squares of
√n × √n cells that split the original matrix.

<p align="center">
  <img src="https://i.imgur.com/OXfL9Gq.png">
</p>

### Input:
The programs accept one command line argument which is the name of a file with the Sudoku instance matrix. 
The format of this file is:
- one line with one integer, l = √n, 2 ≤ l ≤ 9 (specifying l avoids the square root in the code...).
- n lines, each with n integers, separated by a space, with values in the interval [0, n],
where 0s represent blank positions in the matrix.

### Output:
The program outputs (to the stdout) a matrix in the same format as the input:
- n lines, each with n integers, separated by a space, with values in the interval [1, n].

The non-zero values of the input are kept untouched, no zero values should be
present and the matrix should conform with the rules of Sudoku.
In case no solution exists, the program prints "No solution".

<p align="center">
  <img src="https://i.imgur.com/rjxcZSj.png" width="120" height="220">
</p>

### Contributors:

	-Name: 		José Carlos Vieira
	-e-mail:	josecarlosvieira@tecnico.ulisboa.pt
	-Degree: 	MEEC
	
	-Name: 		Manuel Serra Nunes
	-e-mail:	manuelserranunes@tecnico.ulisboa.pt
	-Degree: 	MEEC
  
	-Name:		Pedro Esperança do Carmo
	-e-mail:	pedro.carmo@tecnico.ulisboa.pt
	-Degree:	MEEC

### Institution:

	-Instituto Superior Técnico, Universidade de Lisboa (2017/2018)
