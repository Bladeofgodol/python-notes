### Variables
* There is no command to declare a variable nor do we need to assign a datatype initially. we can just create a variable by assigning to it a value.
    ``` py 
    a = 1;
    b = 'hi'; 
    ```

### Data Types
* There are several data types in python
    * numbers can be `int`, `float` or `complex`
    * texts can be `str`(string)
    * lists can be `list`,`tuple`,`range`
    * mapping can be `dict` (dictionary)
    * booleans are `bool`
    * there can even be `NoneTypes`

## Variables with data type
* If we wish we can initalize using data type.
    ``` py
    c = int(4); 
    ```

## Get data type
* We can return data type of any variable
    ``` py 
    d = 4;
    print(type(d)); 
    ```

## Rules
* We can declare a string with either single or double quote
    ``` py
    e = 'single';
    f = "double" ;
    ```

* Variable names can be short or long and discriptive
    * variable name are case sensetive
        *   ``` py
            g = 'small letter'; 
            G = 'capital letter`; 
            ```
    * A variable name can only start with a letter or the underscore character
        *   ``` py
             _name = 'Dan';
              name = 'Dan';
            ```

    * when using multiple words a a single variable name we can connect them using
        * underscore
            ``` py
            this_is_my_name = 'Dan'; 
            ```

        * capital letters
            ``` py
            ThisIsMyName = 'Dan'; 
            ```

        * cappital letters except for the first one
            ``` py
            thisIsMyName = 'Dan'; 
            ```

* we can assign multiple variables in a single line
    ``` py
    h, i, j = "Dan", 69, 420;
    ```

* we can output a content of a variable with `print()` function
    ``` py
    j = 'this is a code';
    print(j); 
    ```
    ``` this is a code ```

* we can print multiple variables with concatination `(+)`
    ``` py
    k = 'this is a code & ';
    l = ' this is also a code ';
    print(K + l); 
    ```
    ``` this is a code & this is also a code ```

* variables decared outside of functions and classes can be used in classes and functions. this as called  global variables
