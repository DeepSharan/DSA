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
	
	
	
	ALGO TO CHECK WHETHER Number IS PRIME OR NOT
S1 : Start
S2 : initialize variables.
S3 : Read the values.
S4 : If n=0 || n=1 
	Not a prime number
S5 : Repeat the steps until i <= n/2
		If (n % i == 0)
		Not prime number
		else Prime number
S6 : Stop
				   
	CODE
#include <iostream>
using namespace std;
int main()
{
    int i, n;
    bool prime = true;
    
    cout << " Enter a number : ";
    cin >> n ;
    
    if (n == 0 || n == 1)
    {
        cout << n <<" is not a Prime number.";
    }
    
    for(i = 2; i <= n/2; i++ )
    {
        if (n % i == 0)
        prime = false;
    }
    
    if (prime)
    cout <<n <<" is a Prime Number.";
    else
    cout <<n <<" is not a Prime Number.";
    
    return 0;
}

