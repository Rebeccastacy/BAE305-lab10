# BAE305 Lab 10 - Data Informatics

Rebecca Stacy

March 20th, 2024

## Summary

This lab had three parts: create a GitHub account, learn to fork a repository, and learn how to use input and output commands for a data file in python. Since we have done parts one and two in previous labs, the main focus was part 3. For this part, we opened a file from the Data subdirectory containing a limerick, and then wrote code to reverse the characters in the poem and display the backwards poem. In class, we opened the file and displayed the poem, and then tested the code for reversing the file using a shorter string of characters. 

## Code

[Lab 10 full code](https://github.com/Rebeccastacy/HEC-2109-2-Lab1/blob/main/Lab1%20(1).ipynb)

``` python
def reversePoem(instring):
    backPoem = ''
    for x in instring: 
        backPoem = x + backPoem
    return backPoem

# Test it on 'bananas' ...

reversePoem('bananas')

```
## Conclusion

Although we have done parts one and two of this lab previously, forking a repository was a fairly new task for me. However, I was able to complete this part easily with the intruction in class and help from my teammates. Therefore, my main takeaway from this lab was an introduction to python. I have never used python before so this was all brand new to me. This lab was easy to understand because the majority of the code was already written out for us and the purpose of each line was explained in the lecture notebook. The notebook began by opening the limerick as a read only file from the directory, and printing it line by line. It then demonstrated how the open() command allows python to acess and modify files stored on disk. It then created a new file to hold the reversed poem and took the poem data from the original file and made it into a string variable. We were then tasked with writing code to reverse a string and print the characters backwards which is shown in the section of code above as well as the link to the full lecture code. 
