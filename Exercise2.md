## Kode Program Flowchart mengkonversikan dari Fahrenheit ke Celcius dan Reamur
```C
#include <iostream>
using namespace std;
// mengonversikan dari Fahrenheit ke Celcius dan Reamur
int main() 
{ 
	float F, C, R;
	cout << "Input Suhu (Fahrenheit) : ";
	cin >> F;
	C = (F-32)*0.555555556;
	cout << "Celcius : " << C <<endl;
	R = C*0.8;
	cout << "Reamur : " << R;
	
	
	return 0;
}
```
