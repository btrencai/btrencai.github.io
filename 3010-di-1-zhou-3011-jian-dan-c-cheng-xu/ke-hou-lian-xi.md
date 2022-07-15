A

```
#include<stdio.h>
int main(void)
{
   printf("*****\n");
   printf(" ***\n");
   printf("  *\n");
   printf(" ***\n");
   printf("*****\n");
}
```

B

```
#include<stdio.h>
int main(void)
{
   printf("    *\n");
   printf("   ***\n");
   printf("  *****\n");
   printf(" *******\n");
   printf("*********\n");
}
```

C

```
#include <stdio.h>
int main()
{
   int x,y,temp;                              //声明三个整型变量                              
   
   printf("请输入x,y的值:");                  //提示输入数据
   
     scanf("%d,%d",&x,&y);                       //输入2个整数的值，中间用逗号分隔 

  printf("交换前:x = %d , y = %d\n", x,y );   //输出原来的x和y的值
  
  temp=x ;                                   //先把x的值藏一下                                
  x =   y;                                     // 把y的值放到x处 
  y =   temp;                                   //把x的原值放到y处，那么，x的原值藏在哪里呢？
  
   printf("交换后:x = %d , y = %d\n", x,y );   //输出交换后的x和y的值  
}
```

D

```
#include <stdio.h>
int main()
{
   int a,m,f;
   scanf("%d",&a);
f=a+28;
m=f-2;
printf("%d %d",f,m);

}
```

E

```
#include <stdio.h>
int main()
{
   int a,m;
   scanf("%d%d",&a,&m);
printf("%d",a-m);

}
```

F

```
#include <stdio.h>
int main()
{
   int a,m;
   scanf("%d%d",&a,&m);
printf("%d %d %d\n",a+m,a-m,a*m);
printf("%d\n",a+m);
printf("%d\n",a-m);
printf("%d\n",a*m);
}
```

G

```
#include <stdio.h>
int main()
{
   int a,b;
   scanf("%d %d",&a,&b);
   printf("%d %d",a/b,a%b);
}
```

H

```
#include <stdio.h>
int main()
{
   int a,b,sum;
   scanf("%d %d",&a,&b);
   sum=a*b*(b+1)/2;
   printf("%d",sum);
}
```



