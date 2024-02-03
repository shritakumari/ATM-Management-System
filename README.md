# Cpp-codes
Q1) show arithmetic problem 

#include <iostream>
using namespace std;

int main() { 
    int a, b;
    int sum ;
    int difference ;
    int product;
    int div;
    int modulo ;
    
    cout<<"Enter the first no: ";
    cin >>a;
    cout<<"Enter the second no: ";
    cin >>b;
    sum = a+b;
    difference = a-b;
    product = a*b;
    div = a/b;
    modulo = a%b;
    
    cout<<"The sum is: " << sum << endl;
    cout<<"The difference is: " << difference << endl;
    cout<<"The product is: " << product << endl;
    cout<<"The div is: " << div << endl;
    cout<<"The modulo is: " << modulo << endl;
    
    return 0;
}
