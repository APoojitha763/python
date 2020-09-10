LIST IN PYTHON
*****initialising numbers*****
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
****initialising strings****
>>> names=['pooji','malli']
****Two format of list working together****
>>> mill=[nums,names]
>>> mill
[[1, 2, 3, 4, 5], ['pooji', 'malli']]
****Operatios****
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
****Using Inbuilt Functions****
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
>>> max(nums)
10
>>>sum(nums)
38

