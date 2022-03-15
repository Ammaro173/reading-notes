# Read: Class 08

---

> [Back to Home](../README.md)

---

> [references](https://www.pythonforbeginners.com/basics/list-comprehensions-in-python)

## List Comprehensions in Python

> What is it?

    List comprehension is a powerful and concise method for creating lists in Python that becomes essential the more you work with lists, and lists of lists.(remeber It Makes The Code More Readable!!)

### examples

    my_new_list = [ expression for item in list ]

    digits = [x for x in range(10)]

    print(digits) #Output : [0, 1, 2, 3, 4, 5, 6, 7, 8, 9]

    Useful method to to make your Code More Readable!!

    ####################################
    What usually we do is
    data = []
    for x in range(10):
        data.append(x)

    print (data) #Output : [0, 1, 2, 3, 4, 5, 6, 7, 8, 9]

> so we made our code more readable and print 4 lines in 1 Line !!

---

## Lower/Upper case converter using Python

Using list comprehension to loop through a string in Python, it’s possible to convert strings from lower case to upper case, and vice versa.

Making use of Python’s lower() and upper() methods, we’ll use list comprehension to achieve this common task.

Example 6: Changing a letter’s case

    lower_case = [ letter.lower() for letter in ['A','B','C'] ]
    upper_case = [ letter.upper() for letter in ['a','b','c'] ]

    print(lower_case, upper_case)

Output

['a', 'b', 'c'] ['A', 'B', 'C']

---

## Parsing a file using list comprehension

It’s also possible to read files in Python using list comprehension. To demonstrate, I’ve created a file called dreams.txt and pasted the following text, a short poem by Langston Hughes.

Hold fast to dreams
For if dreams die
Life is a broken-winged bird
That cannot fly.
-Langston Hughes

Using list comprehension, we can iterate through the lines of text in the file and store their contents in a new list.

Example 8: Reading a poem with list comprehensions:

    # open the file in read-only mode

    file = open("dreams.txt", 'r')
    poem = [ line for line in file ]

    for line in poem:
    print(line)

Output:

Hold fast to dreams

For if dreams die

Life is a broken-winged bird

That cannot fly.

-Langston Hughs

---

> [Back to Home](../README.md)
