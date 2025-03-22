learning C++ classes at the moment
#include<iostream>
using namespace std;

class person{//making class
public:
int age;
void show(){//making a method
cout<<"My age is:"<<age<<endl;
}

};

int main(){
person human1;//creating object

human1.age = 20;

human1.show();

return 0;
}
