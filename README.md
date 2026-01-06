# Pipex
A program that mimics the behavior of the shell pipe operator `|`.

## Summary
The project explores the design of UNIX systems by re-implementing how the shell handles pipelines and redirections using `pipe()`, `fork()`, `dup2()`, and `execve()`.

## Usage
```bash
# Clone the repository
git clone git@github.com:miluns/pipex.git
cd pipex

# Compile the program
make
