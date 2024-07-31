# LINEAR-SEARCHING-IN-C++
**#include <iostream>
using namespace std;

void search(int arr[], int n, int key) {
    for (int i = 0; i < n; i++) {
        if (arr[i] == key) {
            cout << "Key is present at index " << i << endl;
            return; // Exit the function after finding the key
        }
    }
    cout << "Key not found" << endl;
}

int main() {
    int n;
    cout<<" enter the size of array-->"<<endl;
    cin>>n;
    int arr[100] ;
    cout<<" insert"<<n <<" elment of array--"<<endl;
    for(int i=0;i<n;i++){
        cin>>arr[i];
    }
    cout << "Enter the key: " << endl;
    int key;
    cin >> key;
    
    search(arr, n, key); // Search for the key in the array

    return 0;
}

