### Toolbox: Vim Writeup (Tryhackme)


### Task 1
```
Task 1 is install vim and launch vim
I think you can do it yourself
```
### Task 2
```
#1 Question :How do we enter "INSERT" mode?
   Answer : i
Open Your Teminal and type vim
You reach into vim but this is command mode
You can Change into Insert Mode with shortcut i

#2 Question :How do we start entering text into our new Vim document?
   Answer : typing
   
#3 Question :How do we return to command mode?
   Answer : esc
You can use Esc key to change command mode 

#4 Question :How do we move the cursor left?
   Answer : h
 You can use h to move cursor to left
#5 Question :How do we move the cursor right?
   Answer : l
 You can use l to move cursor to right
 
#6 Question :How do we move the cursor up?
   Answer : k
 You can use k to move cursor to up
 
#7 Question :How do we move the cursor down?
   Answer : j
 You can use j to move cursor to down
 
#8 Question: How do we jump to the start of a word?
   Answer : w 
  You can use w to jump to the start of a word
  
#9 Question: How do we jump to the end of a word?
   Answer : e
  You can use e to jump to the end of a word
  
#10 Question: How do we insert (before the cursor)
    Answer: i
    
#11 Question: How do we insert (at the beginning of the line?)
    Answer: I   

#12 Question: How do we append (after the cursor)
    Answer: a 

#13 Question: How do we append (at the end of the line) 
    Answer : A
#14  Question: How do we make a new line under the current line?
     Answer: o
#15 No Answer Need 
```
### Task 3
```
#1 Question : How do we write the file, but don't exit?
   Answer:   :w
   
#2 Question: How do we write the file, but don't exit- as root?
   Answer:  :w !sudo tee %
   
#3 Question: How do we write and quit?
   Answer:  :wq
   
#4 Question: How do we quit?
   Answer:   :q
   
#5 Question: How do we force quit?
   Answer:  :q!
   
 #6 Question: How do we save and quit, for all active tabs?
    Answer:  :wqa
```

### Task 4
```
#1 Question: How do we copy a line?
   Answer: yy
   
#2 Question: How do we copy 2 lines?
   Answer: 2yy
   
#3 Question: How do we copy to the end of the line?
   Answer:  y$
   
#4 Question: How do we paste the clipboard contents after the cursor?
   Answer: p
   
#5 Question:How do we paste the clipboard contents before the cursor?
   Answer: P
   
#6 Question:How do we cut a line?
   Answer: d
   
#7 Question:How do we cut two lines?
   Answer: 2dd
   
#8 Question:How do we cut to the end of the line?
   Answer: D
   
#9 Question:How do we cut a character?
   Answer: x
```
### Task 5
```
#1 Question:How do we search forwards for a pattern (use "pattern" for your answer)
   Answer: /pattern
   
#2 Question:How do we search backwards for a pattern (use "pattern" for your answer)
  Answer: ?pattern
  
#3 Question:How do we repeat this search in the same direction?
   Answer: n
#4 Question:How do we repeat this search in the opposite direction?
   Answer: N
#5 Question:How do we search for "old" and replace it with "new"
   Answer: :%s/old/new/g
   
#6 Question:How do we use "grep" to search for a pattern in multiple files?
   Answer: :vimgrep
```
