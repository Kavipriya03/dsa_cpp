# dsa_cpp

#include<iostream>
#include<math.h>
#include<string>
using namespace std;
/*
    *       1
   ***      3    
  *****     5    
 *******    7
*/


void oddNumber(int n){
for(int i = 1; i <= n; i++){
      
  for(int j = 1; j<=i; j++){
       
   if(i % 2 == 1){
        cout  << "*" <<" ";
    }
    
    cout <<"";
    }
       
    
    cout<<endl;



}
}

int main (){

    int n;
    cin>>n;
    oddNumber(n);    

    return 0;
}

