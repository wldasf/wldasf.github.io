Simplified Explanation of CPU Cache in the Computer
===================================================

15 Feb, 2025

*What is cache?*<br>
The CPU processes a lot of data, so to make it faster at getting that data and process it the cache stores copies of that data that can be shared quickly with the CPU. There are multiple levels of cache, L1, L2, L3.

L1 is the fastest and holds data you use frequently and it's also closest to the CPU. While L2 and L3 are slower and hold data that you use less often. 

*How does cache work?*<br>
The cache works with something called memory addresses. Think of these as unique labels for each piece of data. When the CPU wants something, it sends out the memory address. The cache is organized so it can quickly check if it has data with that address. If it does, it sends that data right back. If not, the CPU has to go to the much slower main memory(RAM).

*How is cache moved around through L1 to L3?*<br>
Cache uses algorithms to organize data based on hotness and coldness, data that is used a lot and data is that used less often.

Algorithms such Least Recently Used (LRU), and First In First Out (FIFO) are good simplified examples of what is used to organize the data. LRU tries to be clever by kicking out the data you haven't used in the longest time, while FIFO is a bit simpler, just getting rid of whatever's been there the longest. That's how data goes down a level from L1 to L2 or L3. Initially all new data goes to L1 then remains or gets moved based on hotness and coldness.
