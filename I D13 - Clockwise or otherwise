#include<iostream>
#include<vector>
using namespace std;
int main()
{
	vector<int> v;
	int t;
	cin>>t;
	while(t--)
	{
		int n;
		cin>>n;
		string str;
		str.clear();
		cin>>str;
		int count;
		count=0;
		int k;
		k=0;
		for(int i=0;i<n;i++)
		{
			if(str[i]=='1')
			{
				v.push_back(count);
				count=0;
				k++;
			}
			else
			{
				count++;
			}
		}
		v.push_back(count);
		int sum=0;
		for(int i=0;i<=k;i++)
		{
			sum=sum+v[i];
		}
		
		int min;
		min=sum-v[0]-v[k];
		
		//cout<<min<<endl;
		for(int i=1;i<k;i++)
		{
			//cout<<v[i];
			if(sum-v[i]<min)
			{
				min=sum-v[i];
			}
		}
		
		
		cout<<min<<endl;
		v.clear();
		
	}
}
