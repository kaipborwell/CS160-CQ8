# CS160-CQ8
The time complexity of alternatingCharacters recursive function can be expressed as O(n), where n is the length of the input string s. This is because in each recursive call, the function processes one character of the string and makes a recursive call on a substring of size (n-1). The number of recursive calls is proportional to the length of the string, resulting in a linear time complexity.
The space complexity of alternatingCharacters is determined by the depth of the recursive tree where depth is the length of the string s. Therefore the space compleexity is O(n).

The time complexity of the staircase algorithm is O(n^2) because there is a nested for loop that run n times and the for loop inside runs n times as well/ 
The space complexity of the staircase algorithm is O(1) because the space dependencies does not relate to the input n and takes constant space regardless of how large the input parameter n is. 
