# ex02  

## Resource  
[Sed Command in Linux/Unix with examples](https://www.geeksforgeeks.org/sed-command-in-linux-unix-with-examples/)  
[SED command in Linux | Set 2](https://www.geeksforgeeks.org/sed-command-linux-set-2/)  

## command  
```bash
find . -type f -name '*.sh' | sed 's/\.sh$//'
```  

> find_sh.sh  

```bash
#!/bin/bash

find . -type f -name '*.sh' | sed 's/\.sh$//'
```  


![code15](https://github.com/user-attachments/assets/b0fefc41-4941-493c-950c-4d9ed513fec6)  
