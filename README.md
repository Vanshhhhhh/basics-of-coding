# basics-of-coding
//switch statement and other stuff
#include <stdio.h>
#include<bits/stdc++.h>
using namespace std;
int main()
{
    long long n;
    cin>>n;
    long long  i=0;
    long long ans=0;
    while(n!=0)
    {
        long long digit=n%10;// iska andar hum akhri se number uthate ja rahe hain isliye kam kar raha hai linked list leet code ka andar fail ho gya tha ye q-1290
        if(digit==1)
        {
            ans=ans+pow(2,i);
        }
        n=n/10;
        i++;
    }
    cout<<ans<<endl;
    return 0;
}
