# hf#include <conio.h>
#include <stdio.h>
#include <iostream.h>

long gtc(long);
void main()
{
	long n;
	char c;#include <conio.h>
#include <stdio.h>
#include <iostream.h>

long gtc(long);
void main()
{
	long n;
	char c;
	do {
		clrscr();
		do { 	cout << "Nhap so nguyen duong n : ";
			cin >> n;
		} while (n < 1);
		cout << n << "!!=" << gtc(n);
		fflush(stdin);
		cout << "\nTiep tuc ? (c/k):";
		cin >> c;
	} while ((c == 'c') || (c == 'C'));
}

long gtc(long n)
{
	if ((n == 0) || (n == 1)) return 1;
	else return n* gtc(n - 2);
}
		fflush(stdin);
		cout << "\nTiep tuc ? (c/k):";
		cin >> c;
	} while ((c == 'c') || (c == 'C'));
}

long gtc(long n)
{
	if ((n == 0) || (n == 1)) return 1;
	else return n* gtc(n - 2);
}
