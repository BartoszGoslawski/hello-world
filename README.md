#include<iostream>
using namespace std;

int jednaZmienna(){
	cout<<"Podaj sygnal wejsciowy:\n";
	int a;
	cin>>a;
	return a;
}

int dwieZmienne(){
	cout<<"Podaj A oraz B:\n";
	int tab[2];
	cin>>tab[0];
	cin>>tab[1];
	
	int *dajTab(){
		return tab;
	}
}

int fNot(int a){
	if(a==1){	
		cout<<"0";
		return 0;
	}
	else if(a==0){
		cout<<"1";
		return 1;
	}
}
int fAnd(int tab[]){
	//a=a*b;
	cout<<tab[0];
	int dajTab(int){
		return tab;

	}
}

int main()
{
	int a; 
	cout<<"Wybierz funkcje logiczna: \n";
	cout<<"1. AND\n2. NAND\n";
	cout<<"3. OR\n4. NOR\n";
	cout<<"5. XOR\n6. XNOR\n";
	cout<<"7.NOT\n";
	cin>>a;
	switch(a){
		case 1:
			dwieZmienne();
			//fAnd(2,3);
			break;
			
		case 7:
			fNot(jednaZmienna());
			break;
		
	}
}
