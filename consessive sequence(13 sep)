#include <iostream>
#include <vector>
#include<stack>
#include <bits/stdc++.h>
using namespace std;

int main() {
	// your code goes here
	int t=0;
	cin>>t;
	for(int i=0;i<t;i++){
	    int n=0,a,y=0;
	    cin>>n;
	    vector<int> x,res;
	    stack<int> x1,x2;
	    for(int j=0;j<n;j++){
	        cin>>a;
	        x.push_back(a);
	    }
	    sort(x.begin(),x.end());
	    if(x.size()%2==0){
	        for(int p=0;p<n;p++){
	            if(p<n/2){
	                x1.push(x[p]);
	            }
	            else{x2.push(x[p]);}}
	        while(x1.size()!=0){
	            if(x1.top()==x2.top()){y=-1;}
	            res.push_back(x1.top());
	            res.push_back(x2.top());
	            x1.pop();
	            x2.pop();
	        }
	    }
	    else{
	        res.push_back(x[0]);
	        for(int p=1;p<n;p++){
	            if(p<=n/2){
	                x1.push(x[p]);
	            }
	            else{x2.push(x[p]);}}
	        while(!x1.empty()){
	            if(x1.top()==x2.top()){y=-1;}
	            res.push_back(x2.top());
				res.push_back(x1.top());
	            
	            x1.pop();
	            x2.pop();
	        }
	    }
	    for(int k=0;k<n;k++){
	        if(y==-1){cout<<-1;break;}
	        cout<<res[k]<<" ";
	    }
	    cout<<endl;
	}
	return 0;
}
