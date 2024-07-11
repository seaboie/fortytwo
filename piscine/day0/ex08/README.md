# ex08  

## Resource  
- [Use the Unix find command to search for files](https://kb.iu.edu/d/admm)  
- [find()](https://linux.die.net/man/1/find)  
- [Digital Ocean](https://www.digitalocean.com/community/tutorials/how-to-use-find-and-locate-to-search-for-files-on-linux)  

## Command line  

- Lists ไฟล์ ที่หาเจอออกมา

```bash
find . \( -name '*~' -o \( -name '#*' -a -name '*#' \) \) -ls 
```  

- Lists แล้ว Delete ลบ  

```bash
find . \( -name '*~' -o \( -name '#*' -a -name '*#' \) \) -ls -delete
```  

- มี ให้เลือกว่า จะลบ หรือ ไม่ลบ  

```bash
find . \( -name '*~' -o \( -name '#*' -a -name '*#' \) \) -ls -ok rm {} \;  
```  

