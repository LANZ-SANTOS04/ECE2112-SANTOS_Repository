# ECE2112-SANTOS_Repository

# ALPHABET SOUP PROBLEM: 
- Create a function that takes a string and returns a string with its letters in alphabetical order.
- 
**Purpose:**
  
To take a jumbled string of letters
Sort them from A → Z
Return the reordered string

**Example:**
```python
alpha_soup("hello world")
# Output: dehllloorw
```

# EMOTICON PROBLEM 
- Create a function that changes specific words into emoticons. Given a sentence as a string, replace the words smile, grin, sad and mad with their corresponding emoticon

**Purpose:**

- Turn specific feelings written as words into their emoji-like symbols.
ex. "smile" -> ":)"

**Result:**
make me smile -> make me :)


# UNPACKING LIST PROBLEM 
- Unpack the list writeyourcodehere into three variables, being first, middle, and last, with middle being everything in between the first and last element. Then print all three

**Purpose:**

Pull out the first and last values from a list while keeping the rest grouped together

**Example**
```python
lst = [1, 2, 3, 4, 5, 6]
first, *middle, last = lst

#output
first = [1]
middle = [2,3,4,5]
last = [6]
