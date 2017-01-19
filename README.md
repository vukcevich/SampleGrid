# SampleGrid



 Write a Swift playground that takes an n x n grid of integers. Each integer can be either 1 or 0.
 
 The playground then outputs an n x n grid where each block indicates the number of 1's around that block, (excluding the block itself) . For Block 0 on row 0, surrounding blocks are (0,1) (1,0) and (1,1). Similary for block (1,1) all the blocks around it are to be counted as surrounding blocks.
 
 Requirements:
 
 Make sure your solution works for any size grid.
 Spend an hour and a half coding the logic and another hour cleaning your code (adding comments,  cleaning variable and function names).
 
 Optimize your functions to be O(n^2).
 
 Your output lines should not have any trailing or leading whitespaces.
 
 Please use hard coded example input constants below.
 
 Examples:
 
 Input Grid:
 
 let sampleGrid = [[0,1,0], [0,0,0], [1,0,0]]
 
 Console Output:
 
 1 0 1
 2 2 1
 0 1 0
 
 /////////////////
 
 Input Grid:
 
 let sampleGrid = [[0,1,0,0], [0,0,0,1], [1,0,0,1],[0,1,0,1]]
 
 Console Output:
 
 1 0 2 1
 2 2 3 1
 1 2 4 2
 2 1 3 1
 


