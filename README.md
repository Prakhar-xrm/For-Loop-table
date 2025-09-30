#include <stdio.h>
int main(){
  
  int num;
  int i;
  int result;
  
  scanf("%d", &num);
  
  printf("Multiplication Table for %d:\n", num);
  
  
  for(i = 1; i <= 10; i++){
    result = num * i;
    printf("%d X %d = %d\n", num, i, result);
  }
  return 0;
}
