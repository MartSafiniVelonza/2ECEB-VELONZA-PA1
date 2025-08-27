# 2ECEB-VELONZA-PA1

# ALPHABET SOUP
This function receives a string input and returns it as a new string with alphabetically arranged characters.

1. Declare the alphabet_soup function with the string input enclosed by parentheses.

2. Used the sorted() function to arrange the letters of the string input in alphabetical order.

3. Then, use the join() function to combine the sorted characters into one string.

4. The single quotation marks are for the spacing of each letter of the string.

5. At last, print out the sorted string by calling the alphabet_soup function.

OUTPUT
unsorted: feedback
sorted: abcdeefk


# EMOTICON PROBLEM
This function takes a sentence as input and replaces the given words with the corresponding emoticons.

1. Declare the emotify function with a string input called "sentence" enclosed by parentheses.
   
2. Define a dictionary named 'emoticons' that sets the given word with its corresponding emoticons.
    "smile" →  ":)"
    "grin"  →  ":D"
    "sad"   →  ":("
    "mad"   →  ">:("
   
4. Using the split() method, the sentence input will be split into individual words.
   
5. The "result" line is to check all the words in the sentence if they exist in the 'emoticons' dictionary, then replace them with their corresponding emoticons. If not, it remains as is.
   
6. Then combine all the words into a single string using the 'join()' method.
   
7. At last, print out the sorted string by calling the emotify function with the sentence enclosed by parentheses.

INPUT
"When you feel sad"
"or mad about something."
"Think positive and choose to be happy grin"
"Just smile and go on."

OUTPUT
When you feel :(
or >:( about something.
Think positive and choose to be happy :D
Just :) and go on.


# UNPACKING LIST PROBLEMS
This code outputs the first element, the last element, and the elements between them from an array of numbers.

1. List array 'm'

2. Call the index 0 of the array as the first.

3. Call the range of elements between the first and last elements the middle.

4. Call the last element by using '-1' as it returns the last element of any array.

5. At last, print all using "text" comma(,) then the created function format inside the parentheses.

ARRAY
m = [8,16,24,32,40,48]

OUTPUT 
First : 8
Middle : [16, 24, 32, 40]
Last : 48


   
  
