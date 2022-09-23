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

lavanya what lavanya you always reading and writing codes

dey dey this is cheating rawwwww

sare bro meerante unnollu

anthe raww chusara lenollante entha chinna chupoo{}


