# Selction-Sort-C-
//\\Sorting : sorting is techinque to array array itmes in asscending order or decending order.
//\\there are many techinque in sorting :
//	\\ 1) Selction Sorting: note: find the minimum element in a array and swap element in first postion.

#include<iostream>
using namespace std;
int main()	
{
	int n;
	cout<<"Enter array size"<<endl;
	cin>>n;
	int arr[n];
	     cout<<"Enter unsort elements"<<endl;
	
		for(int i=0;i<n;i++)
		{
			
		cin>>arr[i];
		
	}
	for(int i=0;i<n-1;i++)
	{
		for(int j=i+1;j<n;j++)
		{
			if(arr[j]<arr[i])
			{
			
			int temp=0;
		//nt arr[i]=temp;
			temp=arr[j];
			arr[j]=arr[i];
			arr[i]=temp;
		}
		}
		
	}
	for(int i=0;i<n;i++){
	
		cout<<arr[i];
	}

}
	
