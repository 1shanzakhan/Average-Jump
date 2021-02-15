# Average-Jump
C++ Program

#include <iostream>
using namespace std;

    int main()
    {
    	int jump1, jump2, jump3, jump4, average;
        cout<<" Input length of first jump : ";
    	cin>>jump1;
		cout<<" Input length of second jump : ";
    	cin>>jump2;
    	cout<<" Input length of third jump : ";
    	cin>>jump3;
    	cout<<" Input length of fourth jump : ";
    	cin>>jump4;
    	average=((jump1+jump2+jump3+jump4)/4);
        cout<<" The average jump length is : "<< average << endl;
        cout << endl;
        return 0;
    }
