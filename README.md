AIM: To study of loops in Python

THEORY:

A loop in Python is used to execute a block of code repeatedly until a specified condition becomes false. Loops help automate repetitive tasks and make programs efficient.

Python mainly provides two types of loops:

- for loop — used when the number of iterations is known

- while loop — used when the number of iterations is not known in advance

This program focuses on the while loop.

ALGORITHM -

(1). Print i as long as i is less than 6

- Start
- Initialize i = 1

- While i < 6

  ~ Print i

  ~ Increment i by 1

- Stop

(2). Print numbers from 1 to N

- Start

- Input n

- Set i = 1

- While i <= n

  ~ Print i

  ~ Increment i by 1

- Stop

(3). Factorial of a Number

- Start

- Input n

- Set fact = 1

- While n > 0

   ~ Multiply fact = fact × n

   ~ Decrement n by 1

- Print fact

- Stop

(4). Fibonacci Series (n terms)

- Start

- Input n

- Initialize a = 0, b = 1, i = 1

- While i <= n

   ~ Print a

   ~ Set c = a + b

   ~ Set a = b

   ~ Set b = c

   ~Increment i by 1

- Stop

(5). Fibonacci Series up to Limit

- Start

- Input limit

- Initialize a = 0, b = 1

- While a <= limit

   ~ Print a

   ~ Update a = b and b = a + b

- Stop

(6). Reverse a Number

- Start

- Input num

- Set rev = 0

- While num > 0

   ~ Get last digit: digit = num % 10

   ~Update rev = rev × 10 + digit

   ~ Remove last digit: num = num // 10

- Print rev

- Stop

(7). Check Palindrome Number

- Start

- Input num

- Store temp = num

- Set rev = 0

- While num > 0

   ~ rev = rev × 10 + (num % 10)

   ~ num = num // 10

- If temp == rev

   ~ Print "Palindrome"
  
   ~ Else

- Print "Not Palindrome"

-  Stop

(8). Check Palindrome String (Fixed String)

- Start

- Assign string s = "madam"

- Set i = 0, j = length of s - 1

- Set is_palindrome = True

- While i < j

    ~ If s[i] != s[j]

    ~ Set is_palindrome = False

    ~ Break loop

    ~ Increment i, Decrement j

- If is_palindrome is True

   ~ Print "Yes" Else Print "No"

- Stop

(9). Check Palindrome String (User Input)

- Start

- Input string s

- Set i = 0, j = length of s - 1

- Set is_palindrome = True

- While i < j

   ~ If characters at i and j are not equal

   ~ Set is_palindrome = False

   ~ Break

   ~ Increment i, Decrement j

- If is_palindrome is True

- Print "Yes" Else Print "No"

- Stop

(10). Palindrome Using Slicing

- Start

- Input string st

- Reverse string using slicing → rev = st[::-1]

- If st == rev

   ~ Print "Palindrome"
     Else

    ~ Print "Not Palindrome"

- Stop

(11). Count Digits in a Number

- Start

- Input num

- Set count = 0

- While num > 0

   ~  Increment count

    ~ Remove last digit: num = num // 10

- Print count

- Stop

(12). Exit Loop When i is 3

- Start

- Set i = 1

- While i < 6

  ~ Print i

   ~If i == 3

   ~Break loop

   ~Increment i

- Stop

(13). Search an Element in a List

- Start

- Define list nums

- Input key

- Set i = 0

- While i < length of list

   ~ If nums[i] == key

   ~ Print index

   ~ Break

   ~Increment i

- If loop ends without break

- Print "Element not found"

 - Stop

(14). Print Only Odd Numbers (1 to 10)

- Start

- Set i = 0

- While i < 10

    ~ Increment i

    ~ If i is even

    ~ Continue to next iteration

- Print i

- Stop
