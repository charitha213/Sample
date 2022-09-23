class Solution {
public:
    int concatenatedBinary(int n) {
        const long MOD= 1e9+7;
        long long ans=0;
        for (int i=1;i<=n;i++) {
            
            ans=ans<<(long)(log2(i)+1);
            ans=(ans|i)%MOD;
        }
                      return ans%MOD;
        
    }
};




