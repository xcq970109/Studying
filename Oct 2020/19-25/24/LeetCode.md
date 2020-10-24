# 332 Reconstruct Itinerary
Using Euler Path/Cycle

recursive version / iterative version

https://www.geeksforgeeks.org/fleurys-algorithm-for-printing-eulerian-path/

Add the node with 0 degree to the result, because it is an exit of the current graph, 
then continuously do the same process.

# 338 Counting Bits
Bit computation trick

If *n mod 2 == 0*, *n = n/2 << 1* so the 1's in the binary representation are the same;

Else so the 1's in the binary representation are different by 1;

# 341 Flatten Nested List Iterator
recursive version / iterative version

A recursive idea / divide and conquer

# 343 Integer Break

According to derative analysis, try to have more 3 can make the products bigger. 

But when n mod 3 = 1, take one 3 out to make 3\*1 into 2\*2 can enlarge the prodcut.

# 355 Design Twitter
Use timestamp to distinguish the time when each tweet was posted

Use map to store every user's tweet

Use map to store every user's following, every body is follower of himself

Join the tweet map and the following map when compute the NewsFeed

# 365 Water and Jug Problem

There always exists some *a* and *b* so that *ax + by = d* where *d = gcd(x, y)* 

So if *z mod d = 0* then we can find *(a\*z/d)x + (b\*z/d)y = z*
