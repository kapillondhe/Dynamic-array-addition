







# Dynamic-array-addition
Addition of 1D arrays using dynamic initialization.
#include<iostream>
#include<conio.h>
using namespace std;
int main()
{
    int* p1;
    int* p2;
    int* p3;
    int n,m,i;

    cout<<"Enter no of elements for both arrays :"<<endl;
     cin>>n;
    cout<<"For array P1 :"<<endl;
    p1=new int[n];
    cout<<"Enter "<<n<<" no of elements :"<<endl;
      for(i=0;i<n;i++)
      {
          cin>>p1[i];
      }

    cout<<"For array P2 :"<<endl;
    p2=new int[n];
    cout<<"Enter "<<n<<" no of elements :"<<endl;
      for(i=0;i<n;i++)
      {
          cin>>p2[i];
      }

     p3=new int[n];
    cout<<"The sum of arrays is"<<endl;
     for(i=0;i<n;i++)
     {
         p3[i]=p1[i]+p2[i];
        cout<<p3[i]<<" ";
     }


    getch();
    return 0;
}




