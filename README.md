# test
если вы это видите у меня наконец получилось
#include <iostream>
using namespace std;

int sum(int a, int b) {
	return a + b;
}

int mult(int a, int b) {
	return a * b;
}
int main() {
	setlocale(LC_ALL, "rus");
	int a = 0;
	int b = 0;
	cout << "Введите ваше первое число: ";
	cin >> a;
	cout << "Введите ваше второе число: ";
	cin >> b;
	cout << "Произведение ваших чисел: "  << mult(a, b) << endl;
		cout << "Сумма ваших чисел: "  << sum(a, b) << endl;
	system("pause");
	
} 
