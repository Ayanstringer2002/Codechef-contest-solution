#include <bits/stdc++.h>
using namespace std;

#define ll long long
#define vi vector<int>
#define vvi vector<vi>
#define pii pair<int, int>
#define vii vector<pii>
#define rep(i, a, b) for (int i = a; i < b; i++)
#define ff first
#define ss second
#define setBits(x) builtin_popcount(x)
const int N = 1e5 + 2, MOD = 1e9 + 7;


int main()
{
	int t;  cin >> t;
	while (t--)
	{
		int a,b;    cin>>a>>b;
		int p=0;
		int x=0;
		bool flag=false;
		for(int i=0;i<30;i++)
		{
		    int f=(1<<i)&a;
		    int s=(1<<i)&b;
    		if(f!=s)
    		{
    		    if(f!=(1<<i))
    		    x=(x|(1<<i));
    		    p=i;
    		    flag=true;
    		}
		}
		
		if(flag)
		cout<<(x^(1<<p))<<endl;
		else
		cout<<x<<endl;
		
	}
	return 0;
}
