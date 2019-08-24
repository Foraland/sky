# sky
My first respository.
#include <stdio.h>

int main ()
{
 int type;
 	scanf("%d",&type);
 	switch (type)
 	{
 		case 1:
 			printf("一见钟情\n");
			
		case 2:
			printf("二话不说\n");
			break;
		case 3:
			printf("三言两语\n");
			break;
		case 4:
			printf("四面楚歌\n");
			break;
		case 5:
			printf("五彩斑斓\n");
			break;
		case 6:
			printf("六神无主\n");
			break;
		case 7:	
			printf("七步成诗\n");
			break;
		case 8:
			printf("八面玲珑\n");
			break;
		case 9:
			printf("九转功成\n");
			break;
		case 10:
			printf("十年磨剑\n");
			break;
		default:
			printf("花里胡哨\n");
	 }
	 return 0;
  } 
