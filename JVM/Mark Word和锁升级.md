> Mark Word的位长度为JVM的一个Word大小，也就是说32位JVM的Mark Word为32位，64位JVM为64位。Mark Word的位长度不会受到Oop对象指针压缩选项的影响。
> 
* 32位 mark word
<img width="1334" alt="image" src="https://user-images.githubusercontent.com/7061196/221348206-fc32ec12-55a6-42ef-9328-3071b754f4bf.png">

* 64位 mark word
<img width="1333" alt="image" src="https://user-images.githubusercontent.com/7061196/221348259-50f9b5ac-6d60-4f45-9e78-17be1433493f.png">

* 锁升级
<img width="625" alt="image" src="https://user-images.githubusercontent.com/7061196/221391738-f33260fe-7acb-4ba8-b888-ecce6d910a53.png">
