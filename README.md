#include<iostream>
using namespace std;

/*Declaring functions*/
float add(float a, float b)
{
    return (a + b);
}

float subtract(float a, float b)
{
    return (b - a);
}

float multiply(float a, float b)
{
    return ( a * b);
}

float divide(float a, float b)
{
    return ( b / a);
}

int main()
{
    /*calling the functions and storing the returned values*/
    add(5,4);
    cout<<"The sum of 5 and 4 is: "<<add(5,4)<<endl;
    
    subtract(25,77);
    cout<<"The difference between 77 and 25 is:  "<<subtract(25,77)<<endl; 
    
    multiply(15,4);
    cout<<"The product of 15 and 4 is: "<<multiply(15,4)<<endl;
    
    divide(5,100);
    cout<<"100 divided by 5 equals: "<<divide(5,100)<<endl;
    
    return 0;
}
