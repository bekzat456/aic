#include <iostream>
using namespace std;
int main() {
    int n,s=1;
    cin>>n;
    int a[n][n];
    for(int i=0;i<n;i++){
        for(int j=0;j<n;j++){
            cin>>a[i][j];
        }
    }
    for(int i=0;i<n;i++){
        for(int j=0;j<n;j++){
            if(i%2!=0&&a[i][j]%2==0){
               s+=a[i][j];
            }
        }
    }
    cout<<s;
    return 0;
}
4.
#include <iostream>
using namespace std;
int main() {
    int n,s=0,b=0,q=0,m=0;
    cin>>n;
    int a[n][n];
    for(int i=0;i<n;i++){
        for(int j=0;j<n;j++){
            cin>>a[i][j];
        }
    }
