#latihan1

menentukan bilangan terbesar dari beberapa bilangan acak/inputan acak (i=0). yang bebas ditentukan berapa inputannya.
dengan program sebagai berikut :

#include<iostream>

using namespace std;

int main() {
	int i=0;
	int max=0;
	int a,x;

	cout << "masukan jumlah bilangan : ";
	cin >> a;

	for (i;i<a;i++) {
		cout << "masukan bilangan ke-" << i+1 << "; ";
		cin >> x;

		if (x > max)
			max = x;
	}

![Alt text](https://github.com/Rayxxx777/Praktikum3/blob/master/latihan1.png)


#latihan2

menentukan urutan bilangan dari : 
1. terkecil ke besar
2. terbesar ke kecil

dengan inputan a ( bilangan pertama )
	       b ( bilangan ke-dua )
	       c ( bilangan ke-tiga)

jika a > b dan b > c, maka a lebih besar dari b dan c
jika a < b dan b < c, maka c lebih besar dari a dan b

#include<iostream>

using namespace std;
int main(int argc, char const *argv[])
{
	int a,b,c;

	cin >> a >> b >> c;
if(a<b)
{ if(b<c)
	cout << a <<" "<< b <<" "<< c;
else
{if(a<c)
	cout << a <<" "<< c <<" "<< b;
	else
		cout << c <<" "<< a <<" "<< b;
 }

}
else
{ if(a<c)
	cout << b <<" "<< a <<" "<<c;
else
{ if(b<c)
	cout << b <<" "<< c <<" "<<a;
	else
		cout << c <<" "<< b <<" "<<a;

     }

  }
}



}

![Alt text](https://raw.githubusercontent.com/Rayxxx777/Praktikum3/master/latihan2.png)


#latihan3

mencari bilangan tengah dari beberapa inputan acak
dengan a : bilangan pertama
       b : bilangan ke-dua
       c : bilangan ke-tiga

#include <iostream>

using namespace std;
int main()
{
	int a,b,c;

	cout << " masukan nilai pertama : ";
	cin >> a ;
	cout << " masukan nilai ke-dua : ";
	cin >> b ;
	cout << " masukan nilan ke-tiga : ";
	cin >> c ;

	if (a<b){
		if (b<c)
		cout << "nilai tengahnya adalah : "<< b ;
		else{
			if (a<c)
				cout << "nilai tengahnya adalah : "<< c ;
			else
				cout << "nilai tengahnya adalah : "<< a ;
		}	
	}

	else
	{
		if (a<c)
			cout << "nilai tengahnya adalah : "<< a ;
		else
		{
			if(b<c)
				cout << "nilai tengahnya adalah : "<< c ;
			else
				cout << "nilai tengahnya adalah : "<< b ;

		}
	}

return 0;
}

![Alt text](https://github.com/Rayxxx777/Praktikum3/blob/master/latihan3.png)