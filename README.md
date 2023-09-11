#include <iostream>
using namespace std;

int main() {
  int a=45;
  int & b=a;//this is reference variable
  cout<<"the value of a and b is:"<<a<<"\t"<<b<<endl;
  
  
  /*typecasting*/
  float x=54.89;
  cout<<"the value of x is: "<<(int)x;//data type of float change into int type
	return 0;
}
