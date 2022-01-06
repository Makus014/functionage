# functionage



#include <iostream>
using namespace std;


void mall();
void hawaii();
void age(int age);

int main() {
	int user;
	cout << "Type your age!(16-30)" << endl;
	cin >> user;

	age(user);

	return 0;
}

void age(int age) {
	if (age >= 16 && age <= 21) {
		mall();
	}
	else if (age >= 22 && age <= 30) {
		hawaii();
	}
	else {
		cout << "error" << endl;
	}
	
}

void mall() {
	char user;
	cout << "Should we go to the mall?(Y/N)" << endl;
	cin >> user;

	switch (user) {
		{
	case 'Y':
	case 'y':
		cout << "Enjoy the trip!" << endl;
		break;
		}
		{
	case 'n':
	case 'N':
		cout << "cancelled" << endl;
		break;
		}
	default:
		cout << "Error!" << endl;
	}
}

void hawaii() {
	char user;
	cout << "Should we go to Hawaii?(Y/N)" << endl;
	cin >> user;

	switch (user) {
		{
	case 'Y':
	case 'y':
		cout << "Enjoy the trip!" << endl;
		break;
		}
		{
	case 'n':
	case 'N':
		cout << "cancelled" << endl;
		break;
		}
	default:
		cout << "Error!" << endl;
	}
}
