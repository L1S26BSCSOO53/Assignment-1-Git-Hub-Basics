# Assignment-1-Git-Hub-Basics
Assignment 1 Git Hub starting C++Program the sum of first 50 natural numbers
//ZAINAB SHAKOOR
// L1S26BSCS0053
// PROGRAMMING FUNDAMENTALS
// STARTING GITHUB 
// Assignment 1 PROGRAM TO CALCULATE SUM OF FIRST 50 NATURAL NUMBERS
#include<iostream>
using namespace std;
int main()
{
	//SUM OF FIRST 50 NATURAL NUMBERS 

	const int N = 50;
	cout << "SUM OF FIRST" << " " << N << " " << "NATURAL NUMBERS" << endl;
cout << N * (N + 1) / 2 << endl;
	
	int sum = 0;
	cout << "SUM OF FIRST" << " " << N << " " << "NATURAL NUMBERS" << endl;
	for (int i = 1; i <= 50; i++)
	{
		sum += i;
	}
	cout << "SUM OF FIRST" << " " << N << " " << "NATURAL NUMBERS IS" << " " << sum << endl;
	return 0;
	system("pause");
}
/*OUTPUT
SUM OF FIRST 50 NATURAL NUMBERS
1275
SUM OF FIRST 50 NATURAL NUMBERS IS 1275*/
