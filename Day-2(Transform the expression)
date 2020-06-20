#include <iostream>
#include <stack>
#include <cctype>
#include <cstring>
using namespace std;
int main ()
{
int t;
cin>>t;
char str[401];
stack <char> s;
while (t)
{
cin>>str;
int n = strlen (str);int i=0;
while(n){
if(isalpha(str[i])){cout << str[i];}
else if(str[i] == ')' )
{
cout << s.top ();
s.pop ();
}
else if (str[i] != '(' )
s.push (str[i]);
n--;i++;}
cout << "\n";t--;
}
return 0;
}
