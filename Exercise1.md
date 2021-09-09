## Kode Program Flowchart untuk menampilkan deret bilangan 1, 1, 2, 3, 5, 8, 13
```
#include <iostream>
using namespace std;

int main() 
{
    int n, a = 1, b = 1, berikutnya = 0;
    n = 7;
    cout << "Deret Bilangan: ";

    for (int i = 1; i <= n; ++i)
    {
        // Mencetak dua deret bilangan pertama.
        if(i == 1)
        {
            cout << " " << a<<" ";
            continue;
        }
        if(i == 2)
        {
            cout << b << " ";
            continue;
        }
        berikutnya = a + b;
        a = b;
        b = berikutnya;
         // Mencetak deret bilangan berikutnya.
        cout << berikutnya << " ";
    }
    return 0;
}
```
