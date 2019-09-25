# cat

> Print and concatenate files.

- Create new file with cat (press `Ctrl+D` after desired text is inputed)

`cat > {{file}}`    

- Print the contents of a file to the standard output:

`cat {{file}}`


- Concatenate several files into the target file:

`cat {{file1}} {{file2}} > {{target_file}}`

- Append several files into the target file:

`cat {{file1}} {{file2}} >> {{target_file}}`

- Number all output lines:

`cat -n {{file}}`

- Display non-printable and whitespace characters (with `M-` prefix if non-ASCII):

`cat -v -t -e {{file}}`
