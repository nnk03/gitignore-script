# Gitignore Script

A simple script, to add files to gitignore rather than manually typing
the file name

## Running the script

To run the script, type the following inside a git repository (make sure to add
this directory to `PATH` variable)

```sh
gitignore-script <file1> <file2> ... <directory1> <directory2> ...
```

## Potential Issues

1. Currently, not checking if the given file is already present in the gitignore

### Dependencies

1. `realpath` utility
