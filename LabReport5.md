## `Student:`
![image](studentError)
Upon running my code, an `index out of bounds exception` is being thrown. With numerous variables in play, it's challenging to identify which one is causing the issue while traversing my sample array. I was hoping you can help me spot this error and give me some feedback on it. My guess is that my i or j variable is causing this array to get out of the range of length 3 for nums.

## `TA:`
Based on the code you've provided, it seems that the issue might lie within the ranges used when iterating through the `nums` array inside your for loop. I suggest experimenting with the boundaries of the iteration over the `nums` array. Feel free to contact me if you have any further questions or need assistance.

## `Student:`
![image](studentSuccess)
I'm really pleased to share that I managed to resolve the issue! It turned out that the problem stemmed from using `<=` instead of `<` in my loop conditions. I realized that by initializing `i` and `j` to 0, using `<=` would lead to accessing elements beyond the array bounds. Changing it to `<` fixed the problem, and now my code runs smoothly, producing the desired result. It's moments like these that remind me of the importance of paying attention to array indices in programming. If I encounter any more challenges or need further guidance, I won't hesitate to ask. Thanks for your help!
