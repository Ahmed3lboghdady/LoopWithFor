# LoopWithFor
This C++ program showcases two methods for displaying elements of an array. Method 1 prints every second element starting from the first (100, 300, 700). Method 2 prints elements in reverse order from the last to the third (700, 400, 300).
    
    #include <iostream>
    using namespace std;
    //Method 1   //100,300,700
    //int main()
    //{
    //   int nums[]={100,200,300,400,700};  
    //   int numsSize = sizeof(nums)/sizeof(nums [0]);
    //   for(int i=0;i<numsSize;i+=2){
    //    cout<<nums[i]<<"\n";
    //   }
    //
    //    return 0;
    //}
    
    //Method 2        //700,400,300
    int main()
    {
       int nums[]={100,200,300,400,700};  
       int numsSize = sizeof(nums)/sizeof(nums [0]);
       for(int i=numsSize-1;i>1;i--){
        cout<<nums[i]<<"\n";
       }
    
        return 0;
    }
