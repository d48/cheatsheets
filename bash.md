## to debug scripts
  
	$ bash -x myscript.sh

	// or in scripts
	#!/bin/bash

	set -x
  


## curl with method, password and data parameters
  
	$ curl -X DELETE -u "username:password" -d '{"name":"value"}'
  

## to kill jobs
  
	$ jobs 
	$ kill -9 %1

	// or

	$ ps 
	$ ps -9 <jobid>
  
