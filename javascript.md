# JavaScript Notes

Creating a Basic Javascript
- written in plain text, just like HTML/CSS.
- javascript is just a text file but has a j.s file with the name add-content.js
- javascript can live in a seperate folder like css
- case sensitive

Linking to a Javascript file from an HTML page
- use html ```<script>``` element to tell the browser it's coming across a script.
- ```src``` attribute tells where the javascript file is stored

Placing a Script on the page
- you may see JS in the HTML between ```<script></script>``` tags 
    - it's better to put scripts in their *own* files.
- ```document.write()``` writes content into the document **(the webpage)**
    - simple but not the best way to add content 

---

    This one line shows how to use objects and methods.
    Programmers refer to this as *calling* a method of an object

    ```document.write('good afternoon!')```

    document: webpage
    .: member operator (connects the object name and the desired member to access)
    write: **method** of the document. allows new content to be written into the page where the ```<script>``` element sits
    (): parameters. whenever a method requires some information in order to work, the data is given inside the parentheses 

---

JavaScript runs where it is found in the HTML
- when the browser comes across a ```<script>``` element, it stops to load the script, then checks to see if it needs to do anything

Statements
- **Script** - a series of instructions that a computer can follow one-by-one
- **Statement** - each individual instruction or step. should end with a semicolon
  - statements are instructions
  - each one starts on a new line 
  -can be organized into code blocks
  - conditional statements
    - something greater/less than or [ not ] equal to

Comments
- **comments** should be written to explain what your code does
- makes it easier to read and understand 
- helps anyone (and yourself) to read your code 
- **multi-line** - write a comment that stretches to multiple lines ```/*this is an example*/```
- **single line** - write a single-line comment ```/single line ex. won't be processed by javascript editor/``` 
  - often used for short descriptions

  Variables
  - script will have to temporarily store bits of info
  - data/info is stored in variables
  - when writing js you have to tell the interpreter every individual step that you want it to perform.

- EX: width x height = area
in order to tell the script you have to:
  1. remember the  value for width
  2. remember the value for height
  3. multiply w x h to get the area
  4. return the results to the user


- the data is stored in a variable can change (or vary) each time a script runs

---
```var quantity;```
**var** - keyword to create a variable. example for a *keyword*.
**quantity** - variable name 
  - in order to use a variable you much give it a name/identifier
  - if more than one word, written usually in camelCase 
    - first word lower cased, all subsequent words have the first letter capitalized

Six Rules for Variable Names
1. name must BEGIN with a letter, dollar sign, or underscore
- must not start with a number
2. can contain letters, numbers, dollar sign, underscore
- *never* use a dash (-) or period in a name
3. cannot use keywords or reserved words
    - keywords are spexial words that tell the interpreter to do something 
    - reserved words are ones that may be used in a FUTURE version of fJS
4. CASE SENSITIVE
- **different cases = different variables**
5. use a name that describes what info the variable stores
6. for multiple words: (firstSecondThird)
- you can use an underscore but you can't use a dash 

- **booleans** - JavaScript distinguishes between numbers, strings, and ```true``` or ```false```. tells what code should be activated
- **numeric data type** - handles numbers. for tasks involving counting numbers, determining screen size 
- **string data type** - consists of letters and characters. Can be single/double quotes. quotes must match. can be used with any kind of text

[<==back](README.md) 