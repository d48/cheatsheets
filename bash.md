## to debug scripts
  
	$ bash -x myscript.sh

	// or in scripts
	#!/bin/bash

	set -x
  


## curl with method, password and data parameters
  
	$ curl -X DELETE -u "username:password" -d '{"name":"value"}'
  

## view background processes
    
    $ ps auxww

 
## view background process for python SimpleHTTPServer 

    $ ps auxww | grep 'python'
    $ kill <pid> 

    //<pid> from 2nd column

 
## to kill jobs
  
	$ jobs 
	$ kill -9 %1

	// or

	$ ps 
	$ ps -9 <jobid>
  

## to kill job and all child processes from jobid
  
	$ kill -TERM -<jobid>
  

## using awk to get first column from stdin
  
	$ echo "hello dude" | awk '{print $1}'
	// print out hello
  

## character count
  
	$ echo -n "hello dude" | wc -m
	// prints out 10
	// -n option to not print out newline character
  

## deleting files from find command

Flags help in making sure not to break up file names that contain spaces

```
$ find . -name "*conflicted copy*" -print0 | xargs -0 rm
// deletes all files recursively from current directory that contains `conflicted copy` in the file name
```

## To create the symbolic link

```
ln -s /actual/dir/location/ linkname
```
