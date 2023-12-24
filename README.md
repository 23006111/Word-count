# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Start the program

### Step 2: 
Get the text from the user
 
### Step 3:
Write the function to count the words

### Step 4: 
Type the program to get the output

### Step 5:
Print the number of words

### Step 6: 
End the program

## PROGRAM:
## Devoloped by:RAMYA P
## Reference Number:23006111
~~~
def count_words(text):
    words = text.split()
    return len(words)

if__name__ == "__main__":
   user_input = input("Enter a text: ")
   word_count = count_words(user_input)
   print(f"Word count: {word_count}")
~~~


### OUTPUT:
![Screenshot 2023-12-24 165550](https://github.com/23006111/Word-count/assets/145981696/f7ee8620-1210-4877-8dc0-fa4c5e155dc9)




## RESULT:
Thus the program is written to find the word count from a text.
