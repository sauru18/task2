#include<iostream>
using namespace std;
int main()
{
    char operation;
    float num1,num2,result;

    cout << " operation performed in calculator:"<<endl;
    cout << "addition(+)\n"<<endl;
    cout << "subtraction(-)\n"<<endl;
    cout << "multiplication(*)\n"<<endl;
    cout << "division(/)\n"<<endl;
    cout << "enter the operation that want to perfrom:"<<endl;
    cin >> operation;

    cout <<"enter the first numbers:"<<endl;
    cin >> num1;
    cout <<"enter the second numbers:"<<endl;
    cin >> num2;


    switch(operation)
    {
        case '+':
                    result=num1+num2;
                    cout << "\n result is:"<<result;
                    break;

        case '-':
                    result=num1-num2;
                    cout << "\n result is:"<<result;
                    break;

        case '*':
                    result=num1*num2;
                    cout << "\n result is:"<<result;
                    break;   

        case '/':
                    result=num1/num2;
                    cout << "\n result is:"<<result;
                    break; 

        default:
        cout<<"error! operation is wrong";
        break;       

    }
    return 0;
}
