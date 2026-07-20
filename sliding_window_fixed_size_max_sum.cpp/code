class Solution {
  public:
    int maxSubarraySum(vector<int>& arr, int k) {
        int sum =0;
        int low = 0;
        int high = k-1;
        int n = arr.size();
        for(int i =0;i<k;i++){
            sum = sum+arr[i];
        }
        int res = sum;
        while(high<=n-1){
            res = max(res,sum);
            low++;
            sum = sum-arr[low-1];
            high++;
            sum = sum+arr[high];
            
        }
        return res;
            
        }
};
