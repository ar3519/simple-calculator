#include <stdio.h>
#include <stdlib.h>
#include <string.h>
#include <math.h>
int main(int argc, char *argv[])
{
  float num1,num2,ans;char operator;
  printf("Enter calculation:\n\n");
  scanf("%f %c %f", &num1, &operator, &num2);
  switch(operator)
    {
    case '/': ans = num1/num2;
      break;
    case '*': ans = num1*num2;
      break;
    case '+': ans = num1+num2;
      break;
    case '-': ans = num1-num2;
      break;
    case '^': ans = pow(num1,num2);
      break;
    case ' ': ans = sqrt(num2);
      break;
    default: goto fail;
    }
  printf("%.9g%c%.9g =  %.6g\n\n",num1,operator,num2,ans);
  goto exit;
 fail:
  printf("Fail.\n");
 exit:
  return 0;
}
