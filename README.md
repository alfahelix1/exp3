Experiment 3: Study of Tuple in Python

##AIM: To study the tuple data type in Python and understand its properties, creation, and basic operations.

THEORY: A tuple is a built-in data type in Python used to store multiple values in a single variable. Tuples are written using parentheses () and elements are separated by commas.

Characteristics of Tuple

Tuples are ordered
Tuples are immutable (cannot be changed after creation)
Tuples can store different data types
Tuples support indexing, slicing, concatenation, repetition, and built-in functions Because tuples are immutable, they are memory-efficient and faster compared to lists. Tuples are commonly used when data should not be modified, such as fixed records, marks, coordinates, etc.
ALGORITHM:

Program 1: Creation of Tuple with Different Data Types
Program 2: Accessing Tuple Elements using Indexing
Program 3: Demonstration of Immutability (List vs Tuple)
*Program 4: Tuple Repetition and Difference between (10)*5 and (10,)5
Program 5: Tuple Concatenation and Memory Location
Program 6: Demonstrating Immutability using id()
Program 7: List Modification and Memory Location
Program 8: Tuple Operations on Marks
Program 9: Tuple Unpacking (Student Record)
Program 10: Counting Elements in Tuple (Attendance)

Difference between tuple and list 
Use a list when you need a collection of items that may need to be changed, added to, or removed during the program's execution. They offer flexibility for dynamic data manipulation.
Use a tuple when you have a fixed collection of related data where the integrity of the data is important and should not be accidentally altered. Their immutability helps ensure data remains constant and can offer minor performance benefits. 

CONCLUSION: We learned how to create tuples, access their elements using indexing, and perform operations such as concatenation, repetition, counting, and tuple unpacking. The immutability property of tuples was clearly understood by comparing tuples with lists and observing memory locations using the id() function. Built-in functions like max(), min(), len(), sum(), and count() were also used effectively. Thus, this experiment helped in understanding how tuples are efficiently used to store fixed and unchangeable data in Python programs.
