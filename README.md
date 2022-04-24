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
	
	
	
    ALGO TO FIND A FACTORIAL
S1: Start
S2: declare variables 
S3: initialize variables- factorial <- 1
		                  i <- 1
S4: Read value of n
S5: Repeat the steps until i = n
	factorial = factorial * i
	i = i + 1
S6: Print factorial
S7: Stop
	
	CODE
#include<iostream>
using namespace std;

int main()
{
    int n, factorial, i;
    factorial = 1;
    cout << "Enter a positive integer \n";
    cin >> n;
    if (n <= 0)
    cout << "Error !";
    else
    {
        for (i = 1; i <= n; i++)
        factorial *= i;
    }
    cout << "Factorial of "<< n << " is " << factorial;
    return 0;
}
	
	
	
	
