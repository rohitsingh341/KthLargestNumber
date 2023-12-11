# KthLargestNumber

Time Complexity

Inside main method, we iterate through nums array n times (size of nums array). So for this time complexity is O(n)
In the same iteration, we call addNumToHeap() method, this method, adds an element to the heap. This takes O(log k) time.
So overall time complexity is O(n log k)

Space complexity
As we have PriorityQueue to hold top K elements, this takes O(k) space

