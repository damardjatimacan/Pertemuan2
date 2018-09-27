# Pertemuan2 
#include <iostream>

using namespace std;

int main()
{
     int detik, menit, jam, sisajam;   
                cout<<"\n\n Jam ke Menit dan Detik"<<endl;

                cout <<"\n Masukkan detik           : "; cin>> detik;
                jam=detik/3600;
                sisajam=detik%3600;
                menit =menit%60;
                detik = detik%3600;
                cout<<"\n Konversi Waktu Tersebut Adalah "<<endl;
                cout<<"jam : "<<jam;
                cout<<" Menit : "<<menit<<endl;
                cout<<" Detik : "<<detik;
}


