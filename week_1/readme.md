# DSC-DSU | Python Bootcamp 2020 | Week 1
# Assignment no. 1:

**Question no.1:**

**Code:**

name="Khubaib"                          #declare a variable of name

space=""                                #declare a variable for giving whitespace 

for i in range(0,len(name)):            #for executing all the characters of giving string

    print(space+name[i])        #Display the character with space in diagonally
    
    space=space+" "             #for increasing a space for printing a whitespace diagonally after executing the previous character          


**OUTPUT:**

![OUTPUT](https://user-images.githubusercontent.com/49817481/101786162-6df91f00-3b1f-11eb-9956-7ce7e943d1fe.png)

**Question no.3:**

**Code:**

import time

song =["Main tera, Main tera", "Main tera, Main tera", "Main tera, Main tera"] 

def lyrics(song):

  for i in song:
  
    time.sleep(1)
    
    print(i)
    
**OUTPUT:**

![OUTPUT2](https://user-images.githubusercontent.com/49817481/101786924-52dadf00-3b20-11eb-8627-d4d6b0dbc19d.png)




