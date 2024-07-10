# ex07  

## [Linux cat Command:](https://www.hostinger.com/tutorials/linux-cat-command-tutorial-and-examples/)  

## Content of file a  
```
STARWARS
Episode V, A NEW H0PE It is a period of civil war

Rebel spaceships, striking from a hidden base, have won their first victory against the evil Galactic Empire. 
During the battle, Rebel spies managed to steal secret plans to the Empire's ultimate weapon, the STAR DEATH, 
an armored space station with enough power to destroy an entire planet.

Pursued by the Empire's sinister agents, Princess Mehdi races home aboard her starship, custodian of the stolen plans that can save her people and restore the dictatorship to the galaxie..
```  

## Generate `$` charactor at the end of each line  
`
cat -e <fileName>
`
```bash
cat -e a
```  

![code6](https://github.com/seaboie/flutter_trick/assets/96678854/3a94f2d6-1330-44f8-a6d2-9113b8002224)  

## สร้าง ไฟล์ b จาก `cat -e a > b`  
Copy contents from `cat -e a` ไฟล์ `a` ซึ่งเติม `$` ไว้ท้ายบรรทัด และ บรรทัดว่างๆ ไป ใส่ไว้ในไฟล์ `b` ( auto generate file `b`)  

```bash
cate -e a > b
```  

![code7](https://github.com/seaboie/flutter_trick/assets/96678854/89ab941d-034d-4a21-90ea-462e072dc59a)  


## Diff  
> ดูข้อ แตกต่างระหว่าง ไฟล์ `a` และ `b`  
> พร้อมกับ สร้างไฟล์ใหม่ ชื่อ ว่า `sw.diff`

```bash
diff a b > sw.diff
```  

![code8](https://github.com/seaboie/flutter_trick/assets/96678854/7bace450-6dee-438e-bea4-67ded90d0705)  

 




