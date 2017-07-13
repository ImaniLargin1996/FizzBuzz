

/*
---Imani Largin
---7/12/2017
---FizzBuzz Program:
---This program will print out numbers 1-100. But for multiples of 
---3, it will print out Fizz. For multiples of 5, it print out Buzz. 
---For numbers that are multiples of both 3 and 5, it will print out Fizz Buzz
*/
#include <iostream>
using namespace std;

int main()
{
	for (int i = 1;i<101; i++)
	{
		if ((i % 3 == 0) && (i % 5 == 0))
			cout << "FizzBuzz\n";
		else if (i % 3 == 0)
			cout << "Fizz\n";
		else if (i % 5 == 0)
			cout << "Buzz\n";
		else
			cout << i << "\n";
	}
	return 0;
}
