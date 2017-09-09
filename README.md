# vectors
#include<iostream.h>
#include<conio.h>
include<vector>
void display(vector<int>&v)
{
for(int i=0;i<v.size();i++)
{
cout<<v[i];
}
void main()
{
vector<int>v;
cout<<"initial size="<<v.size();
int x;
cout<<"enter five integer value:";
for(int i=0;i<5;i++)
{
cin>>x;
v.push_back(x);
}
cout<<"size after five";
cout<<v.size;
v.push(6.6);
cout<<"now elements:"<<display(v);
vector<int>::iterator itr=v.begin();
itr=itr+3;
v.insert(itr,9);
cout<<"content after inserting";
display(v);
v.erase(v.begin()+3,v.begin()+5);
cout<<"content after deletion:";
display(v);
cout<<endl;
