答えです。

### 練習2
```
#include <stdio.h>

int main(void)
{
  int i,j;

  for(i=1; i<=9; i++) {
    for(j=1; j<=9; j++) {
      printf("%d\t",i*j);
    }
    printf("\n");
  }

  return 0;
}
```


### 練習3
```
#include <stdio.h>

int main(void)
{
  int i,j;

  for(i=1; i<=9; i++) {
    for(j=1; j<=9; j++) {
      printf("%d\t",i*j);
    }
    printf("\n");
  }

  return 0;
}
```


### 練習4
```
#include <stdio.h>

int main(void)
{
  int i;
  int array[10];

  for (i=0; i<10; i++) {
    scanf("%d",&array[i]);
  }

  for (i=9; i>=0; i--) {
    printf("array[%d] = %d\n",i,array[i]);
  }

  return 0;
}
```
