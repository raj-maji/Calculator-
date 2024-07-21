# Calculator-
// This is my calculator 



#include<iostream>

using namespace std;

class A

{
     int a,b,ch,c;
     public:

     void calculator()

                           {

                                         cout<<"enter the two number:";

                                         cin>>a>>b;

                                         cout<<"enter choice for operation";

                                         cin>>ch;

                                        

                                        

                                         if(ch==1)

                                         {

                                                       c=a+b; 

                                                       cout<<"Addition "<<c;

                                                      

                                         }

                                         if(ch==2)

                                         {

                                                       c=a-b;

                                                       cout<<"Subtraction "<<c;

                                         }

                                         if(ch==3)

                                         {

                                                       c=a*b;

                                                       cout<<"Multiplication "<<c;  

                                         }

                                         if(ch==4)

                                         {

                                                       c=a/b;

                                                       cout<<"Devision "<<c;             

                                         }

                                         if(ch==5)

                                         {

                                                       c=a%b;

                                                       cout<<"Modulus "<<c;

                                         }

                                         if(ch>5)

                                         {

                                                      

                                                       cout<<"Invalide Choice ";

                                         }

                                        

             

                           }

             

             

};

int main()

{

              A obj;

              obj.calculator();           

}

