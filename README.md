Remove Duplicates from Sorted Array

📌 Problem

Given a sorted integer array "nums", remove the duplicates in-place so that each unique element appears only once.

Return the number of unique elements.

💡 Example

Input: nums = [1,1,2]

Output: 2

Array after removing duplicates:
[1,2]

💻 Language

Java

📂 File

"RemoveDuplicatesFromSortedArray.java"

🧠 Approach

1. Use an "index" variable to store the position of the next unique element.
2. Traverse the sorted array.
3. Compare the current element with the previous element.
4. If they are different, store the element at the "index".
5. Increase the "index".
6. Return the number of unique elements.

⏱️ Complexity

- Time Complexity: O(n)
- Space Complexity: O(1)

🎯 Goal

To practice arrays and the two-pointer technique in Java.

👨‍💻 Author

K.Leela Sri# Remove-Duplicates-from-Sorted-Array