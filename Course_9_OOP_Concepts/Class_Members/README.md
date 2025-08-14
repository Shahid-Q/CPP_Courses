```cpp

#include <iostream>
using namespace std;

class clsPerson
{
	//this private and will not be accessed from outside the class
	//for internal use only
		int x;
public:
	string FirstName;
	string LastName; // look below

	string FullName()
	{
	return FirstName + LastName;
	}
};

int main()
{
	clsPerson Person1;
	Person1.FirstName = "Mohammed";
	Person1.LastName = "Abu-Hadhoud";

	cout << Person1.FullName() << endl;
	string S1;
}

/*
Class Members:
Data Members: any variable declared inside the class that holds data. (In our case FirstName, LastName are Data Members)
Member Methods: any functions or Procedure declared inside the class. (In our case FullName() is a Member Function/Method
*/
