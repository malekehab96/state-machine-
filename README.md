# state-machine-
#include <stdio.h>
#include <stdlib.h>

int main()
{
int up;
printf("please choose the state\n",up);
scanf("%i", &up);
switch(up){
case 1:
printf("machine is ON");
break;
case 2:
printf("machine is OFF");
break;
case 3:
printf("machine is Working");
break;
case 4:
printf("Robot is Moving");
break;
case 5:
printf("Robot stopped");
break;
case 6:
printf("Connection Error");
break;
case 7:
printf("Wrong State");
break;
case 8:
printf("Connection Returned");
break;
case 9:
printf("Power Low");
break;
case 10:
printf("Power Charging");
break;
}
    return 0;
}
