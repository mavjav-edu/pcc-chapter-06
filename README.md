# Dictionaries 
**Chapter 6** shows you how to use Python’s dictionaries, which let you make connections between different pieces of information. Like lists, dictionaries can contain as much information as you need to store.

TRY IT YOURSELF \#1
-------------------

<span id="ch6exe1"></span>**6-1. Person:** Use a dictionary to store information about a person you know. Store their first name, last name,
age, and the city in which they live. You should have keys such as `first_name`, `last_name`, `age`, and `city`. Print each piece of information stored in your dictionary.

<span id="ch6exe2"></span>**6-2. Favorite Numbers:** Use a dictionary to store people’s favorite numbers. Think of five names, and use them as keys in your dictionary. Think of a favorite number for each person, and store each as a value in your dictionary. Print each person’s name and their favorite number. For even more fun, survey a few friends to get some actual data for your program.

<span id="ch6exe3"></span>**6-3. Glossary:** A Python dictionary can be used to model an actual dictionary. However, to avoid confusion, let’s call it a glossary.

• Think of five programming words you’ve learned about in the previous chapters. Use these words as the keys in your glossary, and store their meanings as values.

• Print each word and its meaning as neatly formatted output. You might print the word followed by a colon and then its meaning, or print the word on one line and then print its meaning indented on a second line.
Use the newline character (`\n`) to insert a blank line between each word-meaning pair in your output.

TRY IT YOURSELF \#2
-------------------

<span id="ch6exe4"></span>**6-4. Glossary 2:** Now that you know how to loop through a dictionary, clean up the code from [Exercise 6-3](#ch6exe3) ([page 102](#page_102)) by replacing your series of `print` statements with a loop that runs through the dictionary’s keys and values. When you’re sure that your loop works, add five more Python terms to your glossary. When you run your program again, these new words and meanings should automatically be included in the output.

<span id="ch6exe5"></span>**6-5. Rivers:** Make a dictionary containing three major rivers and the country each river runs through. One key-value pair might be `'nile': 'egypt'`.

• Use a loop to print a sentence about each river, such as *The Nile runs through Egypt*.

• Use a loop to print the name of each river included in the dictionary.

• Use a loop to print the name of each country included in the dictionary.

<span id="ch6exe6"></span>**6-6. Polling:** Use the code in [*favorite_languages.py*](favorite_languages.py) ([page 104](#page_104)).

• Make a list of people who should take the favorite languages poll.
Include some names that are already in the dictionary and some that are not.

• Loop through the list of people who should take the poll. If they have already taken the poll, print a message thanking them for responding. If they have not yet taken the poll, print a message inviting them to take the poll.

TRY IT YOURSELF \#3
-------------------

<span id="ch6exe7"></span>**6-7. People:** Start with the program you wrote for [Exercise 6-1](#ch6exe1) ([page 102](#page_102)). Make two new dictionaries representing different people, and store all three dictionaries in a list called `people`. Loop through your list of people. As you loop through the list, print everything you know about each person.

<span id="page_115"></span><span id="ch6exe8"></span>**6-8. Pets:** Make several dictionaries, where the name of each dictionary is the name of a pet. In each dictionary, include the kind of animal and the owner’s name. Store these dictionaries in a list called `pets`. Next, loop through your list and as you do print everything you know about each pet.

<span id="ch6exe9"></span>**6-9. Favorite Places:** Make a dictionary called `favorite_places`. Think of three people's names to use as keys  in the dictionary, and store one to three favorite places for each person. What data type will you use to store the one to three favorite places? You could format the places as a [list](https://en.wikiversity.org/wiki/Python_Concepts/Lists), a [tuple](https://en.wikiversity.org/wiki/Python_Concepts/Tuples), or a [set](https://en.wikiversity.org/wiki/Python_Concepts/Sets). To make this exercise a bit more interesting, ask some friends to name a few of their favorite places. Loop through the dictionary, and print each person’s name and their favorite places.

<span id="ch6exe10"></span>**6-10. Favorite Numbers:** Modify your program from [Exercise 6-2](#ch6exe2) ([page 102](#page_102)) so each person can have more than one favorite number. Then print each person’s name along with their favorite numbers.

<span id="ch6exe11"></span>**6-11. Cities:** Make a dictionary called `cities`. Use the names of three cities as keys in your dictionary.
Create a dictionary of information about each city and include the country that the city is in, its approximate population, and one fact about that city. The keys for each city’s dictionary should be something like `country`, `population`, and `fact`. Print the name of each city and all of the information you have stored about it.

<span id="ch6exe12"></span>**6-12. Extensions:** We’re now working with examples that are complex enough that they can be extended in any number of ways. Use one of the example programs from this chapter, and extend it by adding new keys and values, changing the context of the program or improving the formatting of the output.


&nbsp; | &nbsp; | &nbsp; | &nbsp;
----|----|----|----
[&#10094; Prev](../../../pcc-chapter-05)| &nbsp; | &nbsp; | &nbsp;[Next &#10095;](../../../pcc-chapter-07)
