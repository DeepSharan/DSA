# DSA
Let's Learn DSA
/*Algo to Add two numbers eneterd by user
Step1 : Start
Step2 : Declare 2 variables with data type
Step3 : Read values.
Step4 : Add both of them and assign result to sum(or any name you want).
Step5 : Display result
Step6 : Stop 
*/
Code
#include<iostream>
using namespace std;
	
int main()
{
	int a, b, sum;
	cout << "Enter two integers";
	cin >> a >> b;
	sum = a + b ;
	
	cout << "sum = " << sum;
	return 0:
}

	ALGO TO FIND LARGEST NUMBER AMONG 3 NUMBERS
S1: Start
S2: declare variables 
S3: Read variables
S4: If a > b
	    If a > c 
	      Print a is greatest.
	    Else 
	      Print c is greatest.
	  Else
	    If b > c 
	      Print b is greatest.
	    Else 
        Print c is greatest.

S5: Stop
	CODE
#include<iostream>
using namespace std;

int main()
{
    int a, b, c;
    cin >> a >> b >> c;
    
    if (a > b)
    {
        if (a > c)
        cout << a <<" is greater.";
        else 
        cout <<c <<" is greater";
    }
    else
    {
        if (b > c)
        cout <<b <<" is greater";
        else
        cout<<c <<" is greater.";
    }
    return 0;
}
	
	
	
	
