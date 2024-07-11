# ex09 

## Resource
[Youtube](https://www.youtube.com/watch?v=fVOd3Dxifms)  
[A Quick guide to Magic files](https://0xpius.hashnode.dev/a-quick-guide-to-magic-files)  

## ft_magic ไฟล์
content in this file
```
41  string  42  42 file type
```  

## Command line  

- ทดสอบ ทุกไฟล์
```bash
file -m ft_magic *  
```  

- สร้างไฟล์ `ft_magic.mgc`
```bash
file -C -m ft_magic
```  

- ทดสอบ ทุกไฟล์ ด้วย `.mgc` file
```bash
file -m ft_magic.mgc *
```  


![code9](https://github.com/seaboie/flutter_trick/assets/96678854/c1a23037-4799-4c64-9fb8-a0d1ebdd62be)



