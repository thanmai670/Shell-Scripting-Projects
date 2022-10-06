Shell scripting
===============

In this project, I am constructing scripts to do the following:

 * `gordo`:         Find the five folders in the current directory 
                    consuming the most space.

 * `mp3dups`:       Report duplicate MP3s (by file contents, not
                    file name) on a computer.

 * `recap`:         Take a list of names whose first and last names 
                    have been lower-cased, and properly recapitalize
                    them.

 * `oxbane`:        Find all words in English that have x as their
                    second letter, and n as their second-to-last.

 * `rot13`:         Apply rot13 encoding/decoding to standard in.

 * `space-invader`: Replace all spaces in a filename with underscore 
                    for a given directory.

 * `intersect`:     Computes the lines common to two files.

 * `crackgen`:      Generates a password hash file from a dictionary.

 * `passcrack`:     Attempts to crack a password database whose
                    passwords were hashed but not salted using the
                    output of the previous program.

 * `validate`:      Validates a username and password against a
                    database whose passwords have been properly
                    salted and hashed.

Recommended tools: `bash` or `zsh`, `md5sum`, 
                   `diff`, `sort`, `uniq`, `cut`,
                   `sed`, `awk`, `du`. 


Testing
-------

Running `make test` will run all of the scripts against the
supplied test inputs in the `data` directory.  The results will
be dumped into the `results` directory for inspection.

Running `make compare` will `diff` the `results` directory with
the supplied `expected-results` directory, which contains the
output of the tools when run against the provided test inputs
in the `data` directory.



