> **this will be a todo app**

> in this app users will be able to add todo task as many as they want

> user will be able mark the todo with three categories : more important,important , less important

> user will be able to delete the todo .

> and there will be three filters : all, complete, incomplete .

> user will be also able to clear all completed todo

**project structure:**

```python
# First , there will be a static navigation section

# then there will be a header where user will type and add the todo item
# after that there will todoList where every todo items will be displayed
# and for todoList , there will be a single todo component

# finally there will be footer with all the filter items
```

**state management:**

```python
# There will be two features : 1. todo and 2. filtering

# todo list will be an array of objects. and object will look like :
{
    id,
    title,
    category,
    isCompleted,
}
# filtering will have two things .
# one is status(completed/incompleted) and 2nd is category color .
# as user can select multiple colors , so we will set the initial state of the color items is empty array[].
filtering slice will be look like :
{
    status: all,
    color: []
}

```
