#include <iostream>
using namespace std;

int main(){
	int Harga_Sebuah_Pena;
	int Harga_Sebuah_Buku;
	int Harga_Sebuah_Penghapus;
	int Harga_Sebuah_Penggaris;
	
	cin>> Harga_Sebuah_Pena;
	cin>> Harga_Sebuah_Buku;
	cin>> Harga_Sebuah_Penghapus;
	cin>> Harga_Sebuah_Penggaris;
	
	cout<<endl;
	
	cout<<"{###==========List Barang Belanjaan==========###}"<<endl;
	cout<<endl;
	cout<<"Harga 23 buah Buku	= Rp "<< 23*Harga_Sebuah_Pena <<endl;
	cout<<"Harga 23 buah Penghapus 	= Rp "<< 23*Harga_Sebuah_Buku <<endl;
	cout<<"Harga 23 buah Penghapus 	= Rp "<< 23*Harga_Sebuah_Penghapus <<endl;
	cout<<"Harga 23 buah Penggaris 	= Rp "<< 23*Harga_Sebuah_Penggaris <<endl;
	
	return 0;
}
