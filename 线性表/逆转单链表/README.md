###### 三指针法  

* 初始时，p1指向第一个节点，p2指向p1的下一个节点，设置p1的下一个节点为null
* 重复执行下面的过程，一直到p2为null
    * 令p3指向p2的下一个节点
    * 设置p2的下一个节点为p1
    * 令p1 = p2; p2 = p3