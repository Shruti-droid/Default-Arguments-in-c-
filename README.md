# Default-Arguments-in-c-
A program coded in C++ in which if we give two arguments  or three arguments it will provide the correct solution by using the principle of Default Arguments. 

#include<iostream> 
#include<conio.h>
using namespace std;
int add(int,int=0,int=0);
int main()
{
	int a,b,c;
	cout<<"enter two nos.";
	cin>>a>>b;
    cout<<"sum is:" <<add(a,b);
    cout<<"enter three nos.";
	cin>>a>>b>>c;
    cout<<"sum is:" <<add(a,b,c);
    getch();
}
int add(int x,int y,int z)
{
	return(x+y+z);
}
	
