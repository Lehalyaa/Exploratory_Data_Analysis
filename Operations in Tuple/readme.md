# Operations on Tuple
A tuple is a finite ordered sequence of elements that can store elements of multiple data types. While it shares many similarities with lists, its primary difference lies in the property of immutability. In a tuple, once created, any elements can't be added, removed, or modified.

### Aim:
To study the various operations performed on tuples.

### Tools used:
Google Colab or Jupyter Notebook

### Theory:
A tuple is a built-in data type in Python that can store multiple elements of multiple data types. It is considered a dynamic placeholder for various data types. Tuples and lists have many similarities between them, but the difference is their immutability.

Types of tuples:

    **(i) Empty tuple:** 
            A tuple with no elements inside is called an empty tuple. It is just represented by a parenthesis with no character inside, which also includes space.

    **(ii) Filled Tuple:**
            a tuple with a minimum of one or more elements inside. The element may be of any type, and all elements must obey the conventional rules of Python command writing.

**Representation of Tuples:**

Tuples are represented inside parentheses '()', and each element inside it is separated by a comma ','.

**Accessing items in a list:**

Since tuples are stored in an ordered sequence, they can be accessed by indexing, where the indexing rule is the same as that of lists.

**Shared operations between list and tuple:**

* slicing: 
* Membership: 
--> Checking if an item exists can be done in both lists and tuples.
--> It is done by using the 'in' operator.

* len(): 
--> Usage of this operator can be done in both lists and tuples.
--> This is done to know the length of the tuple or list.

**Different operations in lists and tuples:**

Commands such as 'append,' 'insert,' 'remove,' 'pop,' 'sort,' 'reverse,' and 'clear' perform operations on the lists, which can change the outline of the elements in the lists.

Thus, this command can't be used in a tuple, as it is an immutable data type.

If we try to use these commands in tuples, it will raise an error.

### Learning Outcomes:
* Certain commands are present in Python that can be used in lists but not in tuples, because tuples are immutable.
* Using the tuple() command, we can convert any data type into a tuple.
* An integer or float data type cannot be converted into a tuple directly because they're non-iterables.

### Applications of lists:
* Since tuples are immutable, they can be used in data integrity functions where there is no need to change or modify the data.
* It is used in graphics and UI design for defining specific shades of RGB.
* Used in geographical and mapping systems since coordinates represent a specific unchanging point on earth

### Advantages:
* Performance and speed: They are faster than lists since they are immutable.
* Memory Efficiency: tuples used less memory (RAM) than lists.
* Hashability due to its property of immutability

### Conclusion:
 Thus, the basic operations on the tuple have been performed, and it's been seen that tuples are immutable structured sequences of data.
