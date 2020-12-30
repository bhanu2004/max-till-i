// max-till-i
#include <iostream>
using namespace std;
int main()
{
    int n,temp=-999,a;
    cin>>n;
    int arr[n];
    for(int i=0;i<n;i++)cin>>arr[i];
    cin>>a;
    for(int i=0;i<a;i++){
       if(arr[i]>temp){
           temp=arr[i];
       }
    }
    cout<<temp;
}
