# Pipex
A program that mimics the behavior of the shell pipe operator `|`.

## Summary
The project explores the design of UNIX systems by re-implementing how the shell handles pipelines and redirections using `pipe()`, `fork()`, `dup2()`, and `execve()`.

## Build and usage
```bash
# Clone the repository
git clone git@github.com:miluns/pipex.git
cd pipex

# Compile the program
make

# Run the program with compatible input
./pipex infile "cmd1" "cmd2" outfile

example:
./pipex file1 "grep a1" "wc -w" file2
