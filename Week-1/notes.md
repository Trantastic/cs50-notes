# Week One - C

__function__

	#include <stdio.h> //include = include this => stdio.h = standard input and output, this file is related to inputting and outputting
	int main(void) //name of function
	{
		printf("hello, world\n"); //items in "" is a string
	}

outputs "hello, world"

__loop__

	while (true) //an infinite loop
	{
		printf("hello, world\n");
	}

	for (int i = 0; i < 50; i++) //finite loop, only runs when i < 50
	{
		printf("hello, world\n");
	}