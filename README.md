# DevNotes
Commands, Dev notes, and things that can be useful.

## Docker 
```
# See list of containers
docker ps              
docker ps -a 

# Delete container
docker rm ID           
   change ^ by the container ID 

# See list of docker images 
docker images           
docker image rm ID 

# Prune unused images 
docker image prune   
```


## Shell 
```
# Find a word in file using 
$ grep --color 'word' file.txt 

# Find recursively a string in files 
$ grep -R --color 'word' *
$ grep --color -rinw . -e 'word' (Include line)

# Using specific file type
$ grep -R --color 'word' * --include \*.py 

```


-----
You can see more here:
https://omaryahir.blogspot.mx 
