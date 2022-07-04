## [Go to Home Page]() | [Sololearn](https://www.sololearn.com/)

# Samples

01. [x] [reverse]()

## Opening Files
- to read and write the contents of files.
- A file has been opened and used,and then you should close it.
- to use try and finally or use with statements
- Each ASCII character is 1 byte

* **specify the mode:**
    - "r" means open in read mode
    - "r+" means open in read and Write mode
    - "w" means write mode
    - "w+" means write and read mode
    - "a" means append mode
    - "a+" means append and Write mode
    - Adding "b" to a mode opens it in binary mode (Image-Sound)

## Reading Files
- a file that has been opened in text mode can be read using the read method.

* **methods:**
    - "read()" method
    - "readline()"
    - "readlines()" add content to an existing file

## Writing Files
- "write()" method
    - file.write('text') == len('text')
- "writelines()" method


* **modes:**
    - using "w" entire content will be replaced
    - using the "a" method will add a new line