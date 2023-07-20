
## Features
* Display a prompt and wait for the user to type a command. A command line always ends with a new line.
* If an executable cannot be found, print an error message and display the prompt again.
* Handle errors.
* Hndling the “end of file” condition (Ctrl+D)
* Hanling the command line with arguments
* Handle the PATH
* Support the exit features and the exit status
* Handle the Ctrl-C to not terminate the shell
* Handling the command seperator `;`
* Handling `&&` and `||` logical operators
* Handle variable replacements `$?` and `$$`
* Handle the comments `#`
* Support the history feature
* Support the file input

## Builtins
* The exit builtin `exit [STATUS]`
* The change directory `cd [DIRECTORY] | [OPTION]`
* Display the environnment variables `env`
* Initialize a new environnment variables or created if not match `setenv [VARIABLE] [VALUE]`
* Remove an environnment variable `unsetenv [VARIABLE]`
* Support the aliases `alias [name [='value'] ...]`
* Display help `help [BUILTIN]`
* Display history `history`



## Authors
Jeffrey Baah - Software Engineer & Fullstack Developer - [Linkedin](https://www.linkedin.com/in/jeffrey-baah-8bb6b0125/) - [Twitter](https://twitter.com/kofikorang12)
