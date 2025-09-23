# ECE2112 PA1
This repository belongs to Lanz Jeremy M. Santos of 2ECE-C, and it contains the Performance Assessment 1 for Advanced Computer Programming and Algorithms course.

# ALPHABET SOUP PROBLEM: 
- Create a function that takes a string and returns a string with its letters in alphabetical order.

<br />
<br />
  
The task is to create a function that takes a string input and rearranges its letters alphabetically.

We use the following codes to accomplish the requirements:

**CODES**

def alphabet_soup(word): – defines a function that accepts a string argument.

sorted(word) – sorts the characters of the string in alphabetical order.

"".join(...) – joins the sorted list of letters back into a single string.

return – returns the final alphabetically ordered string.

<br />

COMPILE THE CODES

<br />

```python
i = input("Enter a word:") #inputs the word to be sort

def alphabet_word(text):     #defines the function
    letters = list(text)     #turns the word into a list
    letters.sort()           #sorts the list into alphabetical order
    return "".join(letters)  #rejoins the string

print (alphabet_word(i))     #prints the final output
```

<br />

**RESULT**

<br />

<img width="537" height="67" alt="image" src="https://github.com/user-attachments/assets/3fad6a16-85e7-4dff-92eb-0c2d621d07ed" />

<br />

inputted word was - python, which was converted to hnopty because it is alphabetically arranged.

<br />
<br />

# EMOTICON PROBLEM 
- Create a function that changes specific words into emoticons. Given a sentence as a string, replace the words smile, grin, sad and mad with their corresponding emoticon

<br />
<br />

The task is to create a function that changes specific words into emoticons. Given a sentence as a string, replace the words smile, grin, sad, and mad with their corresponding emoticons.

To start the Python code, we need to use the input() function to accept sentences from the user and .replace() to substitute words with emoticons.

We use the following codes to accomplish the requirements:

**CODES**

input("Enter a sentence:") – takes a sentence from the user.

def emotify(sentence): – defines a function that processes the input string.

sentence.replace("word", "emoji") – replaces the target word with its corresponding emoticon.

return sentence – returns the modified string.

print(emotify(text)) – displays the final output.

<br />

COMPILE THE CODES

<br />

```python
text1 = input("Enter a sentence:") #inputs the first sentence
text2 = input("Enter a sentence:") #inputs the second sentence
text3 = input("Enter a sentence:") #inputs the third sentence
text4 = input("Enter a sentence:") #inputs the fourth sentence

def emotify(sentence): #defines the function where specific words are replaced
    sentence = sentence.replace("smile", ":)")  #replaces "smile" with ":)"
    sentence = sentence.replace("grin", ":D")   #replaces "grin" with ":D"
    sentence = sentence.replace("sad", ":((")   #replaces "sad" with ":(("
    sentence = sentence.replace("mad", ">:(")   #replaces "mad" with ">:(")
    return sentence #returns the modified sentence

print("") #prints a blank line for spacing
print(emotify(text1)) #prints the modified version of the first sentence
print(emotify(text2)) #prints the modified version of the second sentence
print(emotify(text3)) #prints the modified version of the third sentence
print(emotify(text4)) #prints the modified version of the fourth sentence
```
<br />

**RESULT**

<br />

<img width="163" height="95" alt="image" src="https://github.com/user-attachments/assets/fb946ac6-e900-4e6a-a817-27ff81f5e99c" />

<br />
<br />

# UNPACKING LIST PROBLEM 
- Unpack the list into three variables, being first, middle, and last, with middle being everything in between the first and last element. Then print all three

<br />

To start the Python code, we use list unpacking with the * operator to separate the first, middle, and last parts of the list.

We use the following codes to accomplish the requirements:

**CODES**

numbers = [1, 2, 3, 4, 5, 6] – creates a list of numbers.

first, *middle, last = numbers – unpacks the list into three parts:

first = first element

middle = all elements in between (collected into a list because of *)

last = last element

print() – displays the values of first, middle, and last.

<br />

COMPILE THE CODES

<br />

```python
numbers = [1, 2, 3, 4, 5, 6] #list of numbers to be unpacked

first, *middle, last = numbers #unpacks into first, middle, and last

print("first:", first)   #prints the first element
print("middle:", middle) #prints the middle elements
print("last:", last)     #prints the last element
```

<br />

**RESULT**

<br />

<img width="229" height="73" alt="image" src="https://github.com/user-attachments/assets/b5d6534a-64d9-4015-b7a7-898cc2bd43a4" />

<br />

# END

**Thank you for reading my README file! If you want to see my jupyter notebook code, just access it through the attached file "SANTOS_PA1.ipynb" in the same repository as this README file.**

<br />

**VERSION HISTORY**

first version: Sep 2, 2025

current version: Sep 23, 2025

(changed whole readme and changed format into more detailed line by line explanation)
