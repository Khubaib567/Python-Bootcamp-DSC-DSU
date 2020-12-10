# DSC-DSU | Python Bootcamp 2020 | Week 1
# Assignment no. 1:

**Question no.1:**

**Code:**

name="Khubaib"                              #Declare a variable of name

space=""                                    #Declare a variable for giving whitespace 

for i in range(0,len(name)):                #for executing all the characters of giving string

    print(space+name[i])        #Display the character with space in diagonally
    
    space=space+" "             #for increasing a space for printing a whitespace diagonally after executing the previous character          


**OUTPUT:**

![OUTPUT](https://user-images.githubusercontent.com/49817481/101786162-6df91f00-3b1f-11eb-9956-7ce7e943d1fe.png)

**Question no.3:**

**Code:**

import time

song =["Main tera, Main tera", "Main tera, Main tera", "Main tera, Main tera"]              #Declare a list (an array) of song lyrics

def lyrics(song):                                                      #Declare function to display the lyrics after one second

  for i in song:                                                       # for display the lyrics in one line 
  
    time.sleep(1)                   #for display the lyrics after 1 second
    
    print(i)                        #for display one lyrics at each second.
    
**OUTPUT:**

![OUTPUT2](https://user-images.githubusercontent.com/49817481/101786924-52dadf00-3b20-11eb-8627-d4d6b0dbc19d.png)




