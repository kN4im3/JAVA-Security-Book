# JAVA 类

##### 什么是类？

- **类**：类是一个模板，它描述一类对象的行为和状态。

  下图中**男孩 (boy)**、**女孩(girl)**为**类（class）**，它们具有共同的特征，都会吃饭、睡觉、跑步。

  ![image-20210123142331934](D:\JAVA代码审计\docs\JavaCode\img\image-20210123141528880.png)

用代码实现人这个类

```java
public class Men(){
	public void eat(){
		System.out.printf("吃饭");
	}
	public void sleep(){
		System.out.printf("睡觉");
	}
	public void run(){
		System.out.printf("跑步");
	}
}
```

