# Max-Consecutive-Ones-using-Java-Leetcode

    class Solution {
        public int findMaxConsecutiveOnes(int[] nums) {
            int count =0;
            int max =0;
            for(int num:nums){
                if(num == 0){
                    
                    count=0;
                }else{
                    count++;
                }
                if(count>max){
                        max = count;
                }
            }
            return max;
        }
    }
