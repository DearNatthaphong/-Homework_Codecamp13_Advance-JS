### Codecamp # 13
    1. นาย ณัฐพงษ์ ทองพึง
    2. Advance JS Part 2_Array Lab # 4
        2.1 Maximal contiguous subarray (**Optional**)
            ให้เขียนฟังก์ชัน getMaxSubSum(arr) ที่ return ผลรวมของ subarray ที่มากที่สุดที่ติดกัน

       getMaxSubSum([-1,2,3,-9]) == 5 (2,3)
       getMaxSubSum([2,-1,2,3,-9]) == 6 (2,-1,2,3)
       getMaxSubSum([-1,2,3,-9,11]) == 11 (11)
       getMaxSubSum([-2,-1,1,2]) == 3 (1,2)
       getMaxSubSum([100,-9,2,-3,5]) == 100 
       getMaxSubSum([1,2,3]) == 6 (1,2,3)


[2,-1,2,3,-9]

เริ่มจาก array ลำดับที่ 0 ( arr[0])
2 = 1
2+(-1) = 1
2+(-1)+2 = 3
2+(-1)+2+3 = 6 ****
2+(-1)+2+3+(-9) = 3

arr[1]
-1 = -1
-1+2 = 1
-1+2+3 = 4 
-1+2+3+(-9) = 5

arr[2]
2 = 2
2+3 = 5
2+3+(-9) = -4

arr[3]
3 = 3
3+(-9) = -6

arr[4]
-9 = -9




