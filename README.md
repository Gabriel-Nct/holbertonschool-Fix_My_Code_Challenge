# Fix My Code Challenge

## Description

**Fix my code** is a new type of project where you'll jump into an existing codebase and fix it! Sometimes you will know the language, sometimes not.

- **Level**: Amateur
- **By**: Guillaume
- **Weight**: 1
- **Your score will be updated as you progress**

## Background Context

Please download the repository [Fix_My_Code_Challenge](https://github.com/holbertonschool/holbertonschool-Fix_My_Code_Challenge) and use it as initial files for all solutions.

**Important**: You should not recode everything, just fix it!

**This project is NOT mandatory** at all. It is 100% optional. Doing any part of this project will add a project grade of over 100% to your average. Your score won't get hurt if you don't do it, but if your current average is greater than your score on this project, your average might go down. Have fun!

## Requirements

### General

- Allowed editors: `vi`, `vim`, `emacs`
- All your files will be compiled on Ubuntu 20.04 LTS
- All your files should end with a new line
- A `README.md` file, at the root of the folder of the project is mandatory

## Tasks

### 0. FizzBuzz

**mandatory**

Please take a look at my implementation of FizzBuzz in Python: [source code](./challenge/0-fizzbuzz.py)

Something is going wrong...

```bash
$ ./0-fizzbuzz.py 50
1 2 Fizz 4 Buzz Fizz 7 8 Fizz Buzz 11 Fizz 13 14 Fizz 16 17 Fizz 19 Buzz Fizz 22 23 Fizz Buzz 26 Fizz 28 29 Fizz 31 32 Fizz 34 Buzz Fizz 37 38 Fizz Buzz 41 Fizz 43 44 Fizz 46 47 Fizz 49 Buzz
$
```

`15` should print `FizzBuzz` not `Fizz`

**Repo:**

- GitHub repository: `holbertonschool-Fix_My_Code_Challenge`
- Directory: `challenge`
- File: `0-fizzbuzz.py`

### 1. Print square

**mandatory**

Please take a look at my implementation of printing a square in Javascript: [source code](./challenge/1-print_square.js)

Something is going wrong...

```bash
$ ./1-print_square.js 4
####
####
####
####
$ ./1-print_square.js 10
################
################
################
################
################
################
################
################
################
################
################
################
################
################
################
################
$
```

`./1-print_square.js 10` should print a square of size 10...

**Repo:**

- GitHub repository: `holbertonschool-Fix_My_Code_Challenge`
- Directory: `challenge`
- File: `1-print_square.js`

### 2. Sort

**mandatory**

Please find here my implementation of sorting arguments in Ruby: [source code](./challenge/2-sort.rb)

Something is going wrong...

```bash
$ ruby 2-sort.rb 12 41 2 C 9 -9 31 fun -1 32
31
32
12
41
2
9
-9
-1
$
```

**Repo:**

- GitHub repository: `holbertonschool-Fix_My_Code_Challenge`
- Directory: `challenge`
- File: `2-sort.rb`

### 3. User password

**mandatory**

Please find here my implementation of a User class in Python: [source code](./challenge/3-user.py)

Something is going wrong...

```bash
$ ./3-user.py
Test User
is_valid_password should return True if it's the right password
$
```

My tests should not print any error...

**Repo:**

- GitHub repository: `holbertonschool-Fix_My_Code_Challenge`
- Directory: `challenge`
- File: `3-user.py`

### 4. Double linked list

**mandatory**

Please find here my implementation of a Double linked list in C: [source code](./challenge/4-delete_dnodeint/)

Something is going wrong...

```bash
$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 main.c free_dlistint.c print_dlistint.c add_dnodeint_end.c delete_dnodeint_at_index.c -o delete_dnodeint
$ ./delete_dnodeint
0
1
2
3
4
98
402
1024
-----------------
0
1
2
3
4
0
402
1024
-----------------
1
2
3
4
0
402
1024
-----------------
2
3
4
0
402
1024
-----------------
3
4
0
402
1024
-----------------
4
0
402
1024
-----------------
0
402
1024
-----------------
402
1024
-----------------
-----------------
-----------------
-----------------
-----------------
-----------------
-----------------
-----------------
-----------------
-----------------
$
```

It doesn't look right...

**Repo:**

- GitHub repository: `holbertonschool-Fix_My_Code_Challenge`
- Directory: `challenge`
- File: `4-delete_dnodeint/`

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/holbertonschool/holbertonschool-Fix_My_Code_Challenge.git
   ```

2. Navigate to the project directory:

   ```bash
   cd holbertonschool-Fix_My_Code_Challenge
   ```

3. For each task, navigate to the respective file and fix the issues described.

4. Test your solutions to ensure they work correctly.

## Good luck and have fun fixing the code! 🐛➡️✅
