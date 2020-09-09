# Lab_1-task_1
Finding factorial in C++

Student name: `Elizaveta`
***
Group number: **13**
***
Specialty: ***DEaWP***

#include <iostream>
void main()
{
	setlocale(LC_CTYPE, "Russian");
	using namespace std;
	float f = 1, a;
	int i;
	cout << "a = ";
    cin >> a;
	for (i = 1; i < a + 1; i++)
	{
		f = f * i;
	}
	cout << "Факториал = " << f << endl;
}
