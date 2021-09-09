## Kode Program Flowchart untuk menampilkan deret bilangan 1, 1, 2, 3, 5, 8, 13
```C
#include <iostream>
using namespace std;

int main()
{
	int n, a, b, c;

	cout << "Program Bilangan Deret \n";
	n = 7;

	b = 1;
	c = 0;
	a = b + c;
	cout << b << " ";
	for(int i = 1; i < n; i++){
		a = b + c;
		c = b;
		b = a;
		cout << a << " ";
	}
	
	return 0;
}
```
