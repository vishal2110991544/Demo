# Demo
the repository is related to demo of cloning
include<iostream>
using namespace std;

int main() {
	
	int a,b;
    cin>>a>>b;
    int n=1;
    int sum=1;
    if (b==0){
     cout<<1;
    }
    else{
      while(n<=b){
        int ans=sum*a;
            sum=ans;
        n=n+1;
       }
       cout<<sum;
    }
    
}
