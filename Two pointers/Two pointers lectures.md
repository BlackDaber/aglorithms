https://www.youtube.com/watch?v=On03HWe2tZM

https://neetcode.io/courses/algorithms/1
https://neetcode.io/courses/dsa-for-beginners/0

https://leetcode.com/discuss/post/1688903/solved-all-two-pointers-problems-in-100-z56cn/

1. Opposite pointers (left → ← right)
2. Fast / Slow pointer (slow++; fast += 2)
3. In-place overwrite (nums[slow] = nums[fast])

let left = 0;
let right = nums.length - 1;

while (left < right) {
    // логика
}

---
let slow = 0;

for (let fast = 0; fast < nums.length; fast++) {
    if (condition) {
        nums[slow] = nums[fast];
        slow++;
    }
}

![[Pasted image 20260429183225.png]]