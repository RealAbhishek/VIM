##VIM Tutorial

###1. Navigation:
The keys `h`, `j`, `k`, and `l` can be used to navigate in a file character by character or line by line, `h` - left, `j` - down, `k` - up, and `l` - right.
To use `b` to move backward word by word, and `w` to move forward word by word.
To move to the top of the file using `1gg` or just `gg`
To move to the nth line use `ngg` or `nG`
Use commands `0` or `^` to move to the beginning of a line. 
To page down - `CTRL+f`, here `f` can be thought of as  forward; and for page up - `CTRL+b` similarly `b` can be thought of as backward
To delete n(5) number of words use `d5w` -- you can think of it as `delete 5 words` and to delete the whole line use `dd`.
You can even use line mode to go to a specific line.  For example, to move to line 22, you would type `:22` and to go to the last line, use `:$`.
The command `x` to delete a character `d` to delete a word



### Commands and Motion:
The command `dw` has two components an operation and a motion `d` is for an operation that is delete operation and `w` is forward motion so when you press `w` then your cursor jumps from word to word so `w` represents a motion and accounts to a word.
All the motion that you have seen so far can be used with a command for example the motion `k` a `l` and all the motion that moves forward backward left and right so if you press `bl` then it will delete the right character. The command `0` takes to from point to the first character of the line so if you use `d0` then it will delete all the characters and words between your current position in the line to the beginning of the line. 

