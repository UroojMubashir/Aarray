#include <iostream>
 using namespace std;
 
  int main()
{
	string snacks[1] [5] = 
	    { "-----","-O-O-", "-@@@-", "-^^^-","-VVV-"};
	    for (int i = 0; i < 5; i++)
	    {
	        for (int j = 0; j < 5; j++){
	            cout<<snacks[i][j]<< "\n";
	        }
	        cout<<endl;
	    }
	    return 0;
	}
