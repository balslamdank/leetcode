class Solution(object):
    def twoSum(self, nums, target):
        """
        :type nums: List[int]
        :type target: int
        :rtype: List[int]
        """
        #example nums = [2,5,6,8] target=11
        for i in range(len(nums)):
            for j in range(i+1, len(nums)):
                if(nums[i] + nums[j]) == target:
                    return(i,j)
        
solution = Solution()
indices = solution.twoSum([3,1,7,4,8], 8)
print(indices)
