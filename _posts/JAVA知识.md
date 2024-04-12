# JAVA知识

Person是一个类，此时没有构建方法，java会默认生成一个public Persion（）{}的构造方法

![image-20240208225303447](D:\typora\image-20240208225303447.png)

这是自己写了一个构造方法，但是这个构造方法每次访问的值都是固定的，如果让他动起来呢？方法是传参

![image-20240208225233642](D:\typora\image-20240208225233642.png)

此时，变量就动态了

![image-20240208225459209](D:\typora\image-20240208225459209.png)

![image-20240208225708090](D:\typora\image-20240208225708090.png)



![image-20240208234613742](D:\typora\image-20240208234613742.png)

定义set方法，首先创建一个要关联class的成员变量，public void set+要关联的class的名称（class 成员变量） this.成员变量=成员变量