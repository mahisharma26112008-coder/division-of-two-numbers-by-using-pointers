# division-of-two-numbers-by-using-pointers

#include<iostream> 
  using namespace std;
   int main(){
       int a,b;
       int *p,*q;
       cout<<"enter the value of a and b :"<<" ";
       cin>>a>>b;
       p=&a;
       q=&b;

       
       cout<<"division of two elements :"<<(*p/ *q);

       return 0;

   }
