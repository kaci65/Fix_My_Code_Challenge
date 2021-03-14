## **Fix-my-code-0**
Check out the existing code base and fix it! The existing code should not be re-coded, it just needs to be fixed

### **0-fizzbuzz.py**
Please take a look at my implementation of FizzBuzz in Python: 
source code<https://github.com/holbertonschool/0x00-Fix_My_Code_Challenge/blob/master/0-fizzbuzz.py>

Something is going wrong…
```
$ ./0-fizzbuzz.py 50
1 2 Fizz 4 Buzz Fizz 7 8 Fizz Buzz 11 Fizz 13 14 Fizz 16 17 Fizz 19 Buzz Fizz 22 23 Fizz Buzz 26 Fizz 28 29 Fizz 31 32 Fizz 34 Buzz Fizz 37 38 Fizz Buzz 41 Fizz 43 44 Fizz 46 47 Fizz 49 Buzz
$
```
15 should print FizzBuzz not Fizz

### **1-print_square.js**
Please take a look at my implementation of printing a square in Javascript: 
source code<https://github.com/holbertonschool/0x00-Fix_My_Code_Challenge/blob/master/1-print_square.js>

Something is going wrong…
```
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
./1-print_square.js 10 should print a square of size 10…

### **2-sort.rb**
Please find here my implementation of sorting arguments in Ruby: 
source code<https://github.com/holbertonschool/0x00-Fix_My_Code_Challenge/blob/master/2-sort.rb>

Something is going wrong…
```
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

### **3-user.py**
Please find here my implementation of a User class in Python: 
source code<https://github.com/holbertonschool/0x00-Fix_My_Code_Challenge/blob/master/3-user.py>

Something is going wrong….
```
$ ./3-user.py 
Test User
is_valid_password should return True if it's the right password
$
```

### **4-delete_dnodeint/**
Please find here my implementation of a Double linked list in C: 
source code<https://github.com/holbertonschool/0x00-Fix_My_Code_Challenge/tree/master/4-delete_dnodeint>

Something is going wrong…
```
$ gcc -Wall -pedantic -Werror -Wextra main.c free_dlistint.c print_dlistint.c add_dnodeint_end.c delete_dnodeint_at_index.c -o delete_dnodeint
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
I don’t look right… Fix me :(
