# Challenge Directory

This directory contains all the broken code files for the Fix My Code Challenge project. Each file has specific issues that need to be identified and fixed.

## Overview

The challenge directory contains 5 tasks across different programming languages:

- Python
- JavaScript
- Ruby
- C

## Task Files

### 0-fizzbuzz.py

**Language**: Python  
**Issue**: The FizzBuzz implementation doesn't correctly handle numbers divisible by both 3 and 5 (like 15)  
**Expected behavior**: Numbers divisible by both 3 and 5 should print "FizzBuzz", not just "Fizz"

### 1-print_square.js

**Language**: JavaScript  
**Issue**: The print square function doesn't print the correct size square  
**Expected behavior**: Should print a square of exactly the size specified by the argument

### 2-sort.rb

**Language**: Ruby  
**Issue**: The sorting algorithm is not working correctly  
**Expected behavior**: Should sort arguments in the correct order

### 3-user.py

**Language**: Python  
**Issue**: The User class password validation is not working properly  
**Expected behavior**: The test should pass without printing errors

### 4-delete_dnodeint/

**Language**: C  
**Issue**: The double linked list delete function has problems  
**Expected behavior**: Should correctly delete nodes at specified indices

## How to Use This Directory

1. Navigate to this directory:

   ```bash
   cd challenge
   ```

2. For each task, examine the code to identify the bug(s)

3. Fix the issues without rewriting the entire code

4. Test your fixes to ensure they work correctly

## Testing Your Solutions

### Python files:

```bash
./filename.py [arguments]
```

### JavaScript files:

```bash
./filename.js [arguments]
```

### Ruby files:

```bash
ruby filename.rb [arguments]
```

### C files:

```bash
# Compile first
gcc -Wall -pedantic -Werror -Wextra -std=gnu89 *.c -o executable_name
# Then run
./executable_name
```

## Important Notes

- **Do not rewrite**: Only fix the existing bugs
- **Maintain code style**: Keep the original coding style as much as possible
- **All files should end with a newline**
- **Test thoroughly**: Make sure your fixes work for all test cases

## Good luck fixing the code! 🔧
