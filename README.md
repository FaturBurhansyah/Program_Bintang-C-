#include <iostream>

using namespace std;

int main() {
int i, j, k,n;
int v,a,b;
 cout<<"Masukkan tinggi : ";cin>>v;
 cout<<endl;
 for (a=1; a<=v; a++) {
 for (b=1; b<=a; b++) {
 cout<<"*";}
 cout<<endl;}
getchar();

cout << "Program Start Diamond \n";

cout << "masukkan tinggi = "; cin >> n; cout<<endl;

for (i = 1; i <=n; i++)

{

for (j = 0; j <(n - i); j++)

cout <<" ";

for (j = 1; j <= i; j++)

 cout <<"*";

for (k = 1; k < i; k++)

cout <<"*";

cout <<"\n";
}
return 0;
}
