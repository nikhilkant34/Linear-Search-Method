# Linear-Search-Method
Function searches an element in an array by traversing through it.

#include <iostream>
using namespace std;
int LSearch(int arr[], n, key)
{
  for(int i=0;i<=n;i++)
  {
    if(arr[i]==key)
      return i;
    else
      return 0;
  }
}
int main()
{
  int n, x;
  cout<<"Ënter the size of array:";
  cin>>n;
  int arr[n];
  cout<<"Enter the elements in the array:"<<endl;
  for(int j=0;j<=n;j++)
  {
    cin>>arr[j];
  }
  cout<<"Enter the element to be searched:";
  cin>>x;
  LSearch(arr[], n, x;);  
}
