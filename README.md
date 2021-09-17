# Skill-lab-With-OOPM
// C++ program to swap two variables
#include <iostream>
using namespace std;

int main()
{
    int a = 5, b = 10, temp;

    cout << "Before swapping." << endl;
    cout << "a = " << a << ", b = " << b << endl;

    temp = a;
    a = b;
    b = temp;

    cout << "\nAfter swapping." << endl;
    cout << "a = " << a << ", b = " << b << endl;

    return 0;
}
  
// C++ program to find even and odd number

#include <iostream>
using namespace std;
int main()
{
    int num1=452;
   // int num2=591;
switch(num1%2){ //this will return either 0 or 1
case 0:
    cout<<num1<<" is a even number";
    break;
case 1:
    cout<<num2<<" is a odd number";
}
getch();
    return 0;
}
  
  // C++ to add two numbers
  
 #include <iostream>
using namespace std;

int main()
{
    int firstNumber, secondNumber, sumOfTwoNumbers;
    
    cout << "Enter two integers: ";
    cin >> firstNumber >> secondNumber;

    // sum of two numbers in stored in variable sumOfTwoNumbers
    sumOfTwoNumbers = firstNumber + secondNumber;

    // Prints sum 
    cout << firstNumber << " + " <<  secondNumber << " = " << sumOfTwoNumbers;     

    return 0;
}
  
