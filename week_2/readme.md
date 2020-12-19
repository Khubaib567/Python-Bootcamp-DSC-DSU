# DSC-DSU | Python Bootcamp 2020 | Week 2

**Question no.1:**
import os
user_input=input("Enter a folder path: ")
List=os.listdir(user_input)
print(f"Here it's a files of given path ",List)
print("\n")
print(f"And Here is the sorted files of given path")
print(sorted(List, reverse=True))
**Output:**
![utilited](https://user-images.githubusercontent.com/49817481/102684382-d0c27880-41f9-11eb-8579-2f01c7fcca6e.png)
