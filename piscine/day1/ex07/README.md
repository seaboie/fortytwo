# ex07  

# Resource  

- [Understanding /etc/passwd File Format](https://www.cyberciti.biz/faq/understanding-etcpasswd-file-format/)  

## Command line  

```bash
cat /etc/passwd | grep -v '^#' | awk 'NR%2==0' | cut -d':' -f1 | rev | sort -r | awk -v start="$FT_LINE1" -v end="$FT_LINE2" 'NR>=start && NR<=end' | paste -sd ', ' - | sed 's/$/./' 
```  


## bash  

```bash

krit@Macintosh ex07 % export FT_LINE1=1
krit@Macintosh ex07 % export FT_LINE2=5
krit@Macintosh ex07 % cat /etc/passwd | grep -v '^#' | awk 'NR%2==0' | cut -d':' -f1 | rev | sort -r | awk -v start="$FT_LINE1" -v end="$FT_LINE2" 'NR>=start && NR<=end' | paste -sd ', ' - | sed 's/$/./'
www_,vamalc_ tsafbrk_,toorsmvc_ toor.
krit@Macintosh ex07 % 

```  

```bash

krit@Macintosh ex07 % export FT_LINE1=1
krit@Macintosh ex07 % export FT_LINE2=9
krit@Macintosh ex07 % cat /etc/passwd | grep -v '^#' | awk 'NR%2==0' | cut -d':' -f1 | rev | sort -r | awk -v start="$FT_LINE1" -v end="$FT_LINE2" 'NR>=start && NR<=end' | paste -sd ', ' - | sed 's/$/./'
www_,vamalc_ tsafbrk_,toorsmvc_ toor,tocevod_ tessaelibom_,svc_ stneveelppa_.
krit@Macintosh ex07 % 

```  
> ## `./r_dwssap.sh `
```bash
krit@Macintosh ex07 % export FT_LINE1=1
krit@Macintosh ex07 % export FT_LINE2=9 
krit@Macintosh ex07 % ./r_dwssap.sh 
www_,vamalc_ tsafbrk_,toorsmvc_ toor,tocevod_ tessaelibom_,svc_ stneveelppa_.
krit@Macintosh ex07 % 
```  





