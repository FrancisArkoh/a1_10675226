# a1_10675226
c++ assignment 
 
 #include<iostream>
#include<cstdlib>
using namespace std;
int main(){
  int a,i ,b = 0;
  cout<<"PRIME CHECKER\n";
    cout << "Enter a number : ";
    cin >> a;
    if (a == 0)
    {
        cout << "\n" << a << " is not prime";
        exit(1);
    }
    else   {
            for(i=2; i < a; i++)
                if (a % i == 0)
                    b++;
    }
    if (b > 1)
 	    cout << "\n" << a<<"\n"<< "The number is not prime.";
    else
        cout << "\n" << a <<"\n"<< "The number is prime.";
    return 0;
}
