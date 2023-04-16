#include <iostream>
using namespace std;
void findPermutations(string str, int l, int r){
   if (l == r)
   cout<<str<<" ";
   else{
   for (int i = l; i <= r; i++){
    swap(str[l], str[i]);
     findPermutations(str, l+1, r);
    swap(str[l], str[i]);
    }
    }
    }
   int main(){
   string str = "WXYZ";
   int n = str.size();
   findPermutations(str, 0, n-1);
   return 0;
  }
