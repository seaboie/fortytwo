# ex06  

[Show all ignored files in git](https://stackoverflow.com/a/24621695)   

## command line  
```bash
find . -type f  | git check-ignore --stdin | cat -e
```  
![code10](https://github.com/seaboie/flutter_trick/assets/96678854/7e8e7209-1caa-45b5-a48f-b49216a074f9)  

## Exercise 06 

> git_ignore.sh  

```bash
#!/bin/bash

find . -type f  | git check-ignore --stdin
```  
> Make `git_ignore.sh` Executable  
```sh
chmod +x git_ignore.sh
```  
> Command  

![code13](https://github.com/user-attachments/assets/ee50b6bd-09ee-4fb3-b399-00222db226dd)




