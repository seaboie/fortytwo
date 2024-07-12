# ex05  

## command line  
```bash  
git log -5 --pretty=format:'%H' | cat -e
```  
```bash 
git log -5 --format='%H' | cat -e
```  
![code11](https://github.com/seaboie/flutter_trick/assets/96678854/cbfe387b-85dd-4b7a-83fc-d5b6ff49fbb9)  

## Exercise 05 

> git_commit.sh  

```bash
#!/bin/bash

git log -5 --format='%H'
```  
> Make `git_commit.sh` Executable  
```sh
chmod +x git_commit.sh
```  
> Command  

![code14](https://github.com/user-attachments/assets/7acdd59c-7bd0-44cc-a1c3-0279b489a936)

