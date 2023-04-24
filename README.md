# fg-hn-
#include <bits/stdc++.h>
using namespace std;
int main() {
int t,n,x ,p;

  cin>>t ;
   while(t--){
     cin>>n>>x;
     if((n<=2)||(x==0)){
       cout<<1<<endl;
     }
     else {
		 p=(n/x)+2;
       cout<<p<<endl;
     }
   }
}
!
!
