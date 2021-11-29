# cplus2.0-whileloopbreak
the number must be divisible by 5

#include <iostream>
using namespace std;

int
main ()
{
 
  int num;
  cout<<" Enter a number: ";
  cin>>num;
  while (num<= 5)
    {
      if (num % 1 == 0)
	cout << num<<"\n";
     num = num + 1;
     
     cout<<" The number you have entered is divisible by 5 "<<"\n";break;
    }
    
}
