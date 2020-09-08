LIST IN PYTHON

>>> nums=[1,2,3,4,5]
>>> nums
[1, 2, 3, 4, 5]
>>> nums[3]
>>> nums[-1]
5
>>> nums[-4]
2
>>> nums[2:3]
[3]
>>> nums[1:3]
[2, 3]
>>> names=['pooji','malli']
>>> mill=[nums,names]
>>> mill
[[1, 2, 3, 4, 5], ['pooji', 'malli']]
>>> nums.append(6)
>>> nums
[1, 2, 3, 4, 5, 6]
>>> nums.insert(0,0)
>>> nums
[0, 1, 2, 3, 4, 5, 6]
>>> nums.remove(6)
>>> nums
[0, 1, 2, 3, 4, 5]
>>> nums.pop(0)
0
>>> nums
[1, 2, 3, 4, 5]
>>> nums.pop()
5
>>> nums
[1, 2, 3, 4]
>>> del nums[2:]
>>> nums
[1, 2]
>>> nums.extend([7,8,9,10])
>>> nums
[1, 2, 7, 8, 9, 10]
>>> min(nums)
1
>>> del nums[2:]
>>> nums
[1, 2]
>>> nums.extend([7,8,9,10])
>>> nums
[1, 2, 7, 8, 9, 10]
>>> min(nums)
1
>>> nums.insert(2,12)
>>> nums.insert(0,24)
>>> nums.insert(4,0)
>>> nums
[24, 1, 2, 12, 0, 7, 8, 9, 10, 66]
>>> sorted(nums)
[0, 1, 2, 7, 8, 9, 10, 12, 24, 66]
