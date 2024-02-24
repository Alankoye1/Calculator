#include <iostream>
#include <cmath>
using namespace std;

int main(){
    double x,y,w,z;
    char op1 ='n', op2 = 'm';

    cout << "Enter the first number: ";
    cin >> x;

    cout << "Enter the second number: ";
    cin >> y;

    cout << "Enter the third number: ";
    cin >> w;

    cout << "Choose a first operation ( + , - , * , / ) ";
    cin >> op1;

    cout << "Choose a first operation ( + , - , * , / ) ";
    cin >> op2;

    if(op1 == '+' && op2 == '+'){
        z = x + y + w;
        cout << z;
    } else if(op1 == '+' && op2 == '-'){
        z = x + y - w;
        cout << z;
    } else if(op1 == '+' && op2 == '*'){
        z = x + y * w;
        cout << z;
    } else if(op1 == '+' && op2 == '/'){
        z = x + y / w;
        cout << z;
    } else if(op1 == '-' && op2 == '+'){
        z = x - y + w;
        cout << z;
    } else if(op1 == '-' && op2 == '-'){
        z = x - y - w;
        cout << z;
    } else if(op1 == '-' && op2 == '*'){
        z = x - y * w;
        cout << z;
    } else if(op1 == '-' && op2 == '/'){
        z = x - y / w;
        cout << z;
    } else if(op1 == '*' && op2 == '+'){
        z = x * y + w;
        cout << z;
    } else if(op1 == '*' && op2 == '-'){
        z = x * y - w;
        cout << z;
    } else if(op1 == '*' && op2 == '*'){
        z = x * y * w;
        cout << z;
    } else if(op1 == '*' && op2 == '/'){
        z = x * y / w;
        cout << z;
    } else if(op1 == '/' && op2 == '+'){
        z = x / y + w;
        cout << z;
    } else if(op1 == '/' && op2 == '-'){
        z = x / y - w;
        cout << z;
    } else if(op1 == '/' && op2 == '*'){
        z = x / y * w;
        cout << z;
    } else if(op1 == '/' && op2 == '/'){
        z = x / y / w;
        cout << z;
    } else{
        cout << "Invaled";
    }

    return 0;
}
