#include<iostream>
#include<vector>
#include<algorithm>
using namespace std;
int main(){
    int n, ele,max;
    cout<<"Enter the NO of elements to be added :\n";
    cin>>n;
    
    vector<int> list;
    
    for(int i=0;i<n;i++){
        cout<<"Enter :";
        cin>>ele;
        list.push_back(ele);
    }
    
     for(int i=0;i<n;i++){
         max=max<list[i]?list[i]:max;
     }
     
     cout<<"Largest number using first approach :"<<max<<endl;
     sort(list.begin(),list.end());
     cout<<"Largest number using second approach :"<<list[list.size()-1]<<endl;
     
    return 0;
}
