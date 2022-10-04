
problem 1 : YOU HAVE GIVEN A  ARRAY/LIST ARR CONSISTING OF 'N' ELEMENTS . THE ARRAY  ONLY CONTAINS 0S,AND 1S . WRITE A SOLUTION TO SORT THIS ARRAY LIST 



METHOD :  I used  " 2 POINTERS APPROACH " for solving this question.



#include <iostream>
using namespace std;

void sortZeroONE(int arr[] , int n ){
    int i = 0 ; 
    int j = n-1;

    while (i<=j){
         if (arr[i]==0){
            i++;
         }
         else if (arr[j]==1){
            j--;
         }
         else {
            swap(arr[i],arr[j]);
            i++;
            j--;
         }
    }
}

int printingArray (int a[] ,int n)
 {
	for (int i = 0;i<n;i++){
		cout<<a[i]<<" ";
    } 
    cout<<endl;
}


int main(){

    int arr[6] = {0,1,0,1,1,0};

    cout<< "before sorting elements of array "<<endl;
    printingArray(arr ,6 );

    
     sortZeroONE(arr , 6);

     cout<<"after sorting "<<endl; 

     printingArray(arr ,6 );



 return 0 ;
    

}
