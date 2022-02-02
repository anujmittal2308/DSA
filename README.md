"# DSA" 
https://cp-algorithms.com/

900
**
**GCD Problem**  **
https://youtu.be/utZcJ0leZ_g 
https://cp-algorithms.com/algebra/euclid-algorithm.html
![image](https://user-images.githubusercontent.com/84795217/148494624-2355a999-161d-4353-b6fd-1fc79f81c298.png)
https://www.codechef.com/problems/FLOW016
![image](https://user-images.githubusercontent.com/84795217/148503803-b7290ab4-32ac-4f0f-80d0-b7036e65f011.png)
https://codeforces.com/problemset/problem/1617/B  
 
 -
 **using sorting in stl**
 ![image](https://user-images.githubusercontent.com/84795217/149651707-fb28b3ef-5c21-4aa7-8b19-956920c53f2a.png)
https://en.cppreference.com/w/cpp/algorithm/sort
![image](https://user-images.githubusercontent.com/84795217/149651720-c972df52-7278-4e76-9a4b-225f85d19af7.png)

** **Mex in array** **
 Note: The MEX of an array is the minimum non-negative integer that is not present in it. For example,

geeksforgeeks.org/combinatorial-game-theory-set-3-grundy-numbers-numbers-and-mex/#:~:text=What%20is%20Mex%3F,not%20present%20in%20the%20set.
https://www.youtube.com/watch?v=JDuVLyKn7Yw.
https://www.youtube.com/watch?v=MboYbpE76js
 my code 
 
 
 
 #include <bits/stdc++.h>
using namespace std;
int main(){
          int n;
          cin>>n;
          int a[n];
          for(int i=0;i<n;i++)
          cin>>a[i];//let array is ={1,3,2,4,0,8,7,6,9}
          //now
          if(n==0){
                    cout<<0;
                  
          }
          else{
          sort(a,a+n);//{0,1,2,3,4,6,7,8,9}
          int ans=-1;
          for(int i=0;i<n;i++){
                    if(a[i]!=i){
                    ans=i;
                    break;
                    }
                    
          }
          if(ans!=-1)
          cout<<ans;
          else
          cout<<n+1;}
}
![image](https://user-images.githubusercontent.com/84795217/151311456-e680523e-572d-4a4e-a61a-feeceaa80655.png)
![image](https://user-images.githubusercontent.com/84795217/151311484-8f294087-34ae-4fef-99db-6a11ee047b33.png)


**binary search** in c++ for competitive programming
https://www.geeksforgeeks.org/binary-search-functions-in-c-stl-binary_search-lower_bound-and-upper_bound/
![image](https://user-images.githubusercontent.com/84795217/152174069-2627764a-66bf-430f-b87d-2e0d0fad5b9c.png)
![image](https://user-images.githubusercontent.com/84795217/152174123-552e4b1f-b613-421c-903b-4cf309f41f64.png)

https://www.codechef.com/wiki/tutorial-binary-search
![image](https://user-images.githubusercontent.com/84795217/152174234-96af23b1-1df6-4b8f-8abc-65ce7c235464.png)
https://en.cppreference.com/w/cpp/algorithm/binary_search
![image](https://user-images.githubusercontent.com/84795217/152174336-f6b3d019-f6f2-42fe-b173-c7422d35f1f7.png)
https://www.topcoder.com/thrive/articles/Binary+Search
![image](https://user-images.githubusercontent.com/84795217/152174480-ca616b2e-69ab-4e7a-a9d7-d98328bdc01a.png)
https://codeforces.com/blog/entry/9901
![image](https://user-images.githubusercontent.com/84795217/152174645-33c5c257-06df-4dde-8b7f-79c0e4acea3c.png)








