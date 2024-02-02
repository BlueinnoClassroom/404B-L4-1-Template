# 404B Lesson 4 Class Exercise - List Manipulations

## Instructions

### Split VS Code Window

You can drag `main.py` tab to the right side of the window to split the window into two panes. This will allow you to see the instructions and the code at the same time.

### Answering

You can answer the questions by writing your answers in the `main.py` file.

You can run the code by clicking the `Run` button on the top right corner of the editor.

The output will be shown in the `Terminal` tab at the bottom of the editor.

## 1. Create a list

```python
empty_list = [ ]
students = ['Harry', 'Ron', 'Hermione', 'Draco']
```

## 2. Get item

```python
students = ['Harry', 'Ron', 'Hermione', 'Draco']

print(students[0])  # --> Harry
print(students[3])  # --> Draco
```

## 3. Replace item

```python
students = ['Harry', 'Ron', 'Hermione', 'Draco']
print(students[3])  # --> Draco

students[3] = 'Neville'
print(students[3])  # --> Neville
```

## 4. Append item

```python
students = ['Harry', 'Ron', 'Hermione', 'Draco']

students.append('Neville')

print(students)  
# --> ['Harry', 'Ron', 'Hermione', 'Draco', 'Neville']
```

## 5. Insert item

```python
students = ['Harry', 'Ron', 'Hermione', 'Draco']

students.insert(3, 'Neville')

print(students)
# --> ['Harry', 'Ron', 'Hermione', 'Neville', 'Draco']
```

## 6. Remove item

```python
students = ['Harry', 'Ron', 'Hermione', 'Neville', 'Draco']

# remove by value
students.remove('Draco')  

# remove by index
del students[4]      

print(students)
# --> ['Harry', 'Ron', 'Hermione', 'Neville']
```

## 7. Loop through a list

```python
students = ['Harry', 'Ron', 'Hermione', 'Draco']

# Option A:
for s in students:
   print(s)

# Option B:
for i in range(len(students)):
   print(students[i])
```

## Questions

1. Given the following String elements:

    ```python
    "It", "was", "a", "stormy", "night"
    ```

   Declare a list containing these elements.

2. Following Q1, write code to insert two additional elements, `"dark"` and `"and"`, at the proper places in the list to produce the following:

    ```python
    ["It", "was", "a", "dark", "and", "stormy", "night"]
    ```

3. Following Q2, write code to change the second element's value to `"IS"`, producing the following:

   ```python
   ["It", "IS", "a", "dark", "and", "stormy", "night"]
   ```

4. Following Q3, write code to remove from the list any Strings that contain the letter `"a"`.\
   The following should be the list's contents after your code has executed:

   ```python
   ["It", "IS", "stormy", "night"]
   ```

5. Declare a list holding the first 10 multiples of 2: 0, 2, 4, . . . , 18.\
Use a loop to fill the list with the proper elements.

   ```python
   [0, 2, 4, 6, 8, 10, 12, 16, 18]
   ```

6. Write a function called `fill()` that accepts two parameters:
   - A list
   - An integer

   Then replaces every value in the list with that integer value.\
    For example, if a variable called my_list initially stores `[42, -7, 3, 0, 15]` and the call of `fill(my_list, 2)` is made, the list will be changed to `[2, 2, 2, 2, 2]`.

   ```python
   def fill(...):
       ...
       
   my_list = [42, -7, 3, 0, 15]
   my_list = fill(my_list, 2)
   
   print(my_list)
   # --> [2, 2, 2, 2, 2]
   ```

## Submitting Your Work

1. Make sure the assignment repository is opened in VS Code.

2. Make sure you have completed all the tasks.

3. (First time only)
Use Command + J to open the Terminal tab and config your git username and email:

    ```bash
    git config user.name "Your Name"
    git config user.email "Your GitHub Email"
    ```

4. Click on the "Source Control" icon on the left. Source Control

    ![1](https://github.com/BlueinnoClassroom/404B-L2.1-Template/assets/155412668/2c31026e-c14d-484f-bb9e-dc87189a0216)

5. Enter a commit message and click on the "Commit" button.

6. Click on the "Sync Changes" button.
