#include<iostream>
#include<algorithm>
using namespace std;
int main()
{
    int n;
    cin>>n;
    while(n--)
    {
        int a,b;
        cin>>a>>b;
        int x[a+1],i,j,k=0;
        for(i=0; i<a; i++)
        {
            cin>>x[i];
        }
        sort(x,x+a);
        for(j=a-1;j>=0;j--){
  k+=x[j];
  if(k>=b)break;
        }
        if(j==-1)cout<< "0\n" ;
        else cout<<x[j]<<endl;
    }
    return 0;
}
