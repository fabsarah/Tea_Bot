# Tea_Bot
A charming AI for tea drinkers

This bot takes day and time parameters and recommends a tea based on past tea-drinking habits. [There's a blog post explaining the hows and whys here](https://www.armcintosh.com/blog/blog15) and to make it work, you will need a matrix of tea selections! The columns need to be organized as follows:

    Column 1 = Counter (keeps track of trial number)
    Column 2 = Day (1:7 with 1 corresponding to Monday)
    Column 3 = Time. Here, 1:3 correspond to morning, afternoon, and evening
    Columns 4-10 log what tea you have! Each column is a different tea, and the functions use 1s and 0s. I've coded my columns as follows:
        Column 4 = Yorkshire Tea 
        Column 5 = Yunnan Gold
        Column 6 = Assam
        Column 7 = Ruby Tea
        Column 8 = Decaf Breakfast
        Column 9 = Ginger
        Column 10 = No tea 

These have been hard-coded in based on what I drink most commonly, so take some time and play with it!

Happy steeping!
