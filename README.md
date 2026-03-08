# Lower-Bound
class Solution{
public:
    int lowerBound(vector<int> &nums, int x){
        int n=nums.size();
        for(int i=0;i<n;i++){
            if(nums[i]==x){
                return i;
               // break;
            }
            else if(nums[i]>=x){
                return i;
               // break;
            }
        }
        return 0;
    }
};
