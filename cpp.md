#include<iostream> 
using namespace std;
 struct comlexCls{ 
    private: 
    double re=0,img=0; 
    public: 
    complexCls()=delete; 
    comlexCls(double r,double i){img=i;re=r;} 
    double gerRe(void){return re;} 
    double getImg(void){retrun img;}
 };
 void f1(void){ 
    complexCls c1(2,3);
cout<<c1.getRe()<<endl;
} 
int main (){f1();return 0;}
