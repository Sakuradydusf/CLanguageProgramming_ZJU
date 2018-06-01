 # CLanguageProgramming_ZJU

## 章节
* [第1章](#第1章)
* [第2章](#第2章)
* [第3章](#第3章)
* [第4章](#第4章)
* [第5章](#第5章)
* [第6章](#第6章)
* [第7章](#第7章)
* [第7章](#第8章)
* [第9章](#第9章)
* [第10章](#第10章)
* [第11章](#第11章)
* [第12章](#第12章)

## 第1章
1. 

2. **改写1.4节中的流程图1.2，求1~100中能被6整除的所有整数的和**<br />
![1至100之间所有偶数的和](resource/images/1.2.2.png "1至100之间所有偶数的和")
![1至100之间能被6整除的所有数的和](resource/images/1.2.2.png "1至100之间能被6整除的所有数的和")

3. **改写1.4节中的程序，1~100之间能被6整除的所有整数的和**<br />
```c
#include <stdio.h>

int main() {
	int sum = 0;
	int i;
	for (i=1; i<100; i++) {
		if (i%6 == 0) {
			printf("i=%d sum=%d\n", i, sum);
			sum += i;
		}
	}
	printf("sum=%d\n", sum);
	return 0;
} 
```

4. **对于给定的整数n(n>1)，请设计一个流程图判别n是否为素数（只能被1和自己整除的整数），并分析流程图哪些是顺序结构、分支结构与循环结构**
![1至100之间所有的素数](https://user-images.githubusercontent.com/39354920/40822774-5bc1ab74-65a0-11e8-8ab7-e32b10598d84.png "1至100之间所有的素数")
## 第2章

## 第3章

## 第4章

## 第5章

## 第6章

## 第7章

## 第8章

## 第9章

## 第10章

## 第11章

## 第12章
