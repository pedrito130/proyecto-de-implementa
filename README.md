# proyecto-de-implementa

#include <iostream>
using namespace std;
int main()
{
float pulgada,metros,cm,kilometros,r;
float op;
float c;

cout<<"escribe el numero de la opcion que mecesitas:"<<endl;
cout<<"1. millas a pulgadas"<<endl;
cout<<"2. millas a metros"<<endl;
cout<<"3. millas a centimetros"<<endl;
cout<<"4 millas a kilometros"<<endl;
cin>>op;

if (op=1)
cout<<"escribe la cantidad en millas: ";
cin>>c;
r=c*63360;
cout<<"la cantidad en pulgadas es:"<<r<<endl;

if (op=2)
cout<<"escribe la cantidad en millas: ";
cin>>c;
r=c*1609.34;
cout<<"la cantidad en metros es: "<<r<<endl;

if (op=3)
cout<<"escribe la cantidad en millas: ";
cin>>c;
r=c*160934;
cout<<"la cantidad en centimetros es: "<<r<<endl;

if (op=4)
cout<<"escribe la cantidad en millas: ";
cin>>c;
r= c* 1.60934;
cout<<"la cantidad en kilometros es: "<<r<<endl;
    return 0;
}
