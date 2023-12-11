# KthLargestNumber

Time Complexity

Inside the main method, we iterate through the nums array n times (size of nums array). So for this, the time complexity is O(n)
In the same iteration, we call the addNumToHeap() method, this method, adds an element to the heap. This takes O(log k) time.
So, the overall time complexity is O(n log k)

Space complexity

As we have PriorityQueue to hold the top k elements, this takes O(k) space

