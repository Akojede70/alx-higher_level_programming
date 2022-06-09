## Python - More Data Structures: Set, Dictionary


**0-square_matrix_simple.py:** Writing a function that computes the square value of all integers of a matrix.
Prototype: def square_matrix_simple(matrix=[]):
matrix is a 2 dimensional array.
Returns a new matrix:
Same size as matrix.
Each value should be the square of the value of the input.
Initial matrix should not be modified.
You are not allowed to import any module.
You are allowed to use regular loops, map, etc.


**1-search_replace.py:** Writing a function that replaces all occurrences of an element by another in a new list.
Prototype: def search_replace(my_list, search, replace):
my_list is the initial list.
search is the element to replace in the list.
replace is the new element.
You are not allowed to import any module.


**2-uniq_add.py:** Writing a function that adds all unique integers in a list (only once for each integer).
Prototype: def uniq_add(my_list=[]):
You are not allowed to import any module.


**3-common_elements.py:** Writing a function that returns a set of common elements in two sets.
Prototype: def common_elements(set_1, set_2):
You are not allowed to import any module.


**4-only_diff_elements.py:** Writing a function that returns a set of all elements present in only one set.
Prototype: def only_diff_elements(set_1, set_2):
You are not allowed to import any module.


**5-number_keys.py:** Writing a function that returns the number of keys in a dictionary.
Prototype: def number_keys(a_dictionary):
You are not allowed to import any module.


**6-print_sorted_dictionary.py:** Writing a function that prints a dictionary by ordered keys.
Prototype: def print_sorted_dictionary(a_dictionary):
You can assume that all keys are strings.
Keys should be sorted by alphabetic order.
Only sort keys of the first level (don’t sort keys of a dictionary inside the main dictionary).
Dictionary values can have any type.
You are not allowed to import any module.


**7-update_dictionary.py:** Writing a function that replaces or adds key/value in a dictionary.
Prototype: def update_dictionary(a_dictionary, key, value):
key argument will be always a string.
value argument will be any type.
If a key exists in the dictionary, the value will be replaced.
If a key doesn’t exist in the dictionary, it will be created.
You are not allowed to import any module.


**8-simple_delete.py:** Writing a function that deletes a key in a dictionary.
Prototype: def simple_delete(a_dictionary, key=""):
key argument will be always a string.
If a key doesn’t exist, the dictionary won’t change.
You are not allowed to import any module.


**9-multiply_by_2.py:** Writing a function that returns a new dictionary with all values multiplied by 2.
Prototype: def multiply_by_2(a_dictionary):
You can assume that all values are only integers.
Returns a new dictionary.
You are not allowed to import any module.


**10-best_score.py:** Writing a function that returns a key with the biggest integer value.
Prototype: def best_score(a_dictionary):
You can assume that all values are only integers.
If no score found, return None.
You can assume all students have a different score.
You are not allowed to import any module.


**11-multiply_list_map.py:** Writing a function that returns a list with all values multiplied by a number without using any loops.
Prototype: def multiply_list_map(my_list=[], number=0):
Returns a new list:
Same length as my_list.
Each value should be multiplied by number.
Initial list should not be modified.
You are not allowed to import any module.
You have to use map.
Your file should be max 3 lines.


**12-roman_to_int.py:** Technical interview preparation:
You are not allowed to google anything.
Whiteboard first.
Creating a function def roman_to_int(roman_string): that converts a Roman numeral to an integer.
You can assume the number will be between 1 to 3999.
def roman_to_int(roman_string) must return an integer.
If the roman_string is not a string or None, return 0.


**100-weight_average.py:** Writing a function that returns the weighted average of all integers tuple (<score>, <weight>).
Prototype: def weight_average(my_list=[]):
Returns 0 if the list is empty.
You are not allowed to import any module.
  
  
**101-square_matrix_map.py:**  Writing a function that computes the square value of all integers of a matrix using map
Prototype: def square_matrix_map(matrix=[]):
matrix is a 2 dimensional array.
Returns a new matrix:
Same size as matrix.
Each value should be the square of the value of the input.
Initial matrix should not be modified.
You are not allowed to import any module.
You have to use map.
You are not allowed to use for or while.
Your file should be max 3 lines. 
  
  
**102-complex_delete.py:** Writing a function that deletes keys with a specific value in a dictionary.
Prototype: def complex_delete(a_dictionary, value):
If the value doesn’t exist, the dictionary won’t change.
All keys having the searched value have to be deleted.
You are not allowed to import any module.
  
 
**103-python.c:** Creating two C functions that print some basic info about Python lists and Python bytes objects.
Python lists:
Prototype: void print_python_list(PyObject *p);
Format: see example.
Python bytes:
Prototype: void print_python_bytes(PyObject *p);
Format: see example.
Line “first X bytes”: print a maximum of 10 bytes.
If p is not a valid PyBytesObject, print an error message (see example).
Read /usr/include/python3.4/bytesobject.h.
You are not allowed to use the following macros/functions:
Py_SIZE.
Py_TYPE.
PyList_GetItem.
PyBytes_AS_STRING.
PyBytes_GET_SIZE.
  
  
**0-print_dlistint.c:** Writing a function that prints all the elements of a dlistint_t list.
Prototype: size_t print_dlistint(const dlistint_t *h);
Return: the number of nodes.
Format: see example.


**1-dlistint_len.c:** Writing a function that returns the number of elements in a linked dlistint_t list.
Prototype: size_t dlistint_len(const dlistint_t *h);


**2-add_dnodeint.c:** Writing a function that adds a new node at the beginning of a dlistint_t list.
Prototype: dlistint_t *add_dnodeint(dlistint_t **head, const int n);
Return: the address of the new element, or NULL if it failed.


**3-add_dnodeint_end.c:** Writing a function that adds a new node at the end of a dlistint_t list.
Prototype: dlistint_t *add_dnodeint_end(dlistint_t **head, const int n);
Return: the address of the new element, or NULL if it failed.


**4-free_dlistint.c:** Writing a function that frees a dlistint_t list.
Prototype: void free_dlistint(dlistint_t *head);


**5-get_dnodeint.c:** Writing a function that returns the nth node of a dlistint_t linked list.
Prototype: dlistint_t *get_dnodeint_at_index(dlistint_t *head, unsigned int index);
where index is the index of the node, starting from 0.
if the node does not exist, return NULL.


**6-sum_dlistint.c:** Writing a function that returns the sum of all the data (n) of a dlistint_t linked list.
Prototype: int sum_dlistint(dlistint_t *head);
if the list is empty, return 0.


**7-insert_dnodeint.c, 2-add_dnodeint.c, 3-add_dnodeint_end.c:** Writing a function that inserts a new node at a given position.
Prototype: dlistint_t *insert_dnodeint_at_index(dlistint_t **h, unsigned int idx, int n);
where idx is the index of the list where the new node should be added. Index starts at 0.
Returns: the address of the new node, or NULL if it failed.
if it is not possible to add the new node at index idx, do not add the new node and return NULL.

Your files 2-add_dnodeint.c and 3-add_dnodeint_end.c will be compiled during the correction.


**8-delete_dnodeint.c:** Writing a function that deletes the node at index index of a dlistint_t linked list.
Prototype: int delete_dnodeint_at_index(dlistint_t **head, unsigned int index);
where index is the index of the node that should be deleted. Index starts at 0.
Returns: 1 if it succeeded, -1 if it failed.


**100-password:** Finding the password for crackme4.
Save the password in the file 100-password.
Your file should contain the exact password, no new line, no extra space.
Hint: The program prints “OK” when the password is correct.


**102-result:** A palindromic number reads the same both ways. The largest palindrome made from the product of two 2-digit numbers is 9009 = 91 × 99.
Find the largest palindrome made from the product of two 3-digit numbers.
Save the result in the file 102-result.
Your file should contain the exact result, no new line, no extra space.


**103-keygen.c:** Writing a keygen for crackme5.
Usage of the crackme: ./crackme5 username key.
The crackme will segfault if you do not enter the correct key for the user.
Usage for your keygen: ./keygen5 username.
Your keygen should print a valid key for the username.

