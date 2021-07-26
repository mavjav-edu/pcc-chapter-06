# Dictionaries

In this chapter you’ll learn how to use Python’s dictionaries, which
allow you to connect pieces of related information. You’ll learn how to
access the information once it’s in a dictionary and how to modify that
information. Because dictionaries can store an almost limitless amount
of information, I’ll show you how to loop through the data in a
dictionary. Additionally, you’ll learn to nest dictionaries inside
lists, lists inside dictionaries, and even dictionaries inside other
dictionaries.

## TRY IT YOURSELF #1

<span id="ch6exe1"></span>**6-1. Person:** Use a dictionary to store
information about a person you know. Store their first name, last name,
age, and the city in which they live. You should have keys such as
`first_name`, `last_name`, `age`, and `city`. Print each piece of
information stored in your dictionary.

<span id="ch6exe2"></span>**6-2. Favorite Numbers:** Use a dictionary to
store people&rsquo;s favorite numbers. Think of five names, and use them as
keys in your dictionary. Think of a favorite number for each person, and
store each as a value in your dictionary. Print each person&rsquo;s name and
their favorite number. For even more fun, poll a few friends and get
some actual data for your program.

<span id="ch6exe3"></span>**6-3. Glossary:** A Python dictionary can be
used to model an actual dictionary. However, to avoid confusion, let&rsquo;s
call it a glossary.

- Think of five programming words you&rsquo;ve learned about in the previous
chapters. Use these words as the keys in your glossary, and store their
meanings as values.

- Print each word and its meaning as neatly formatted output. You might
print the word followed by a colon and then its meaning, or print the
word on one line and then print its meaning indented on a second line.
Use the newline character (`\n`) to insert a blank line between each
word-meaning pair in your output.

## TRY IT YOURSELF #2

<span id="ch6exe4"></span>**6-4. Glossary 2:** Now that you know how to
loop through a dictionary, clean up the code from [Exercise
6-3](../../../pcc_2e/tree/master/chapter_06/README.md#ch6exe3) ([page 102](../../../pcc_2e/tree/master/chapter_06/README.md#page_102)) by replacing
your series of `print` statements with a loop that runs through the
dictionary&rsquo;s keys and values. When you&rsquo;re sure that your loop works, add
five more Python terms to your glossary. When you run your program
again, these new words and meanings should automatically be included in
the output.

<span id="ch6exe5"></span>**6-5. Rivers:** Make a dictionary containing
three major rivers and the country each river runs through. One
key-value pair might be `'nile': 'egypt'`.

- Use a loop to print a sentence about each river, such as *The Nile
runs through Egypt*.

- Use a loop to print the name of each river included in the dictionary.

- Use a loop to print the name of each country included in the
dictionary.

<span id="ch6exe6"></span>**6-6. Polling:** Use the code in
*favorite_languages.py* ([page 104](../../../pcc_2e/tree/master/chapter_06/README.md#page_104)).

- Make a list of people who should take the favorite languages poll.
Include some names that are already in the dictionary and some that are
not.

- Loop through the list of people who should take the poll. If they have
already taken the poll, print a message thanking them for responding. If
they have not yet taken the poll, print a message inviting them to take
the poll.

## TRY IT YOURSELF #3

<span id="ch6exe7"></span>**6-7. People:** Start with the program you
wrote for [Exercise 6-1](../../../pcc_2e/tree/master/chapter_06/README.md#ch6exe1) ([page
102](../../../pcc_2e/tree/master/chapter_06/README.md#page_102)). Make two new dictionaries representing
different people, and store all three dictionaries in a list called
`people`. Loop through your list of people. As you loop through the
list, print everything you know about each person.

<span id="page_115"></span><span id="ch6exe8"></span>**6-8. Pets:** Make
several dictionaries, where the name of each dictionary is the name of a
pet. In each dictionary, include the kind of animal and the owner&rsquo;s
name. Store these dictionaries in a list called `pets`. Next, loop
through your list and as you do print everything you know about each
pet.

<span id="ch6exe9"></span>**6-9. Favorite Places:** Make a dictionary
called `favorite_places`. Think of three names to use as keys in the
dictionary, and store one to three favorite places for each person. To
make this exercise a bit more interesting, ask some friends to name a
few of their favorite places. Loop through the dictionary, and print
each person&rsquo;s name and their favorite places.

<span id="ch6exe10"></span>**6-10. Favorite Numbers:** Modify your
program from [Exercise 6-2](../../../pcc_2e/tree/master/chapter_06/README.md#ch6exe2) ([page
102](../../../pcc_2e/tree/master/chapter_06/README.md#page_102)) so each person can have more than one favorite
number. Then print each person&rsquo;s name along with their favorite numbers.

<span id="ch6exe11"></span>**6-11. Cities:** Make a dictionary called
`cities`. Use the names of three cities as keys in your dictionary.
Create a dictionary of information about each city and include the
country that the city is in, its approximate population, and one fact
about that city. The keys for each city&rsquo;s dictionary should be something
like `country`, `population`, and `fact`. Print the name of each city
and all of the information you have stored about it.

<span id="ch6exe12"></span>**6-12. Extensions:** We&rsquo;re now working with
examples that are complex enough that they can be extended in any number
of ways. Use one of the example programs from this chapter, and extend
it by adding new keys and values, changing the context of the program or
improving the formatting of the output.

