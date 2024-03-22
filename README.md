#include <bits/stdc++.h>
using namespace std;
bool EsMultiploDe3(int n);


int main() {
	int num;
	string msg="No es multiplo";
	cout<<"ingresar un numero"<<endl;
	cin>>num;
	
		if(EsMultiploDe3(num)){
			msg="Es Multiplo";
		}
		cout<<msg<<endl;
		
	return 0;
}

	bool EsMultiploDe3(int n){
		bool flag=false;
			if(n%3==0){
				flag=true;
			}
			return flag;
	}
