#include<iostream>
using namespace std;

void main()
{
	setlocale(LC_ALL, "ru");
	int a, b, selection;
	cout << "Введите 2 числа: " << endl;
	cin >> a >> b;

	cout << "Какое арифметическое действие выполнить? " << endl
		<< "1. Сложение " << endl
		<< "2. Вычетание " << endl
		<< "3. Умножение " << endl
		<< "4. Деление " << endl;
	
	cin >> selection;

	switch (selection)
	{
	case 1:
		cout << "Сложение двух чисел: "<< (a+b) << endl;
		break;
	case 2:
		cout << "Вычетание двух чисел: " << (a-b) << endl;
		break;
	case 3:
		cout << "Умножение двух чисел: " << (a*b)<< endl;
	case 4:
		cout << "Деление двух чисел: " << (float) a/b<< endl;
	default:
		break;
	}
}
