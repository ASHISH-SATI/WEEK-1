# WEEK-1
#include<iostream.h>
#include<conio.h>
void lsearch(int arr[],int n,int ele);
void main()
{
	clrscr();
	int arr[5];
	int n;
	int ele;
	cout<<"ENTER THE NUMBER OF ELEMENTS";
	cin>>n;
	for(int i=0;i<n;i++)
	{
		cout<<"ENTER ELEMENT";
		cin>>arr[i];
		
	}
	cout<<"ENTER THE ELEMENT TO SEARCH";
	cin>>ele;
	lsearch(arr,n,ele);
	getch();
	
}
void lsearch(int arr[],int n,int ele)
{
	int flag=0;
	for(int i=0;i<n;i++)
	{
		if(arr[i]==ele)
		{
			flag 1;
			break;
		}
	}
}
if(flag==1)
{
	cout<<"ELEMENT FOUND";
	
}
else
{
	cout<,"ELEMENT NOT FOUND!!";
}
