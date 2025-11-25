## Loops in Python: Palindrome Number Checker

## Aim
To write a Python program that checks whether a given number is a **palindrome** using loops.

## Algorithm
1. Get input from the user and assign it to a variable `num`.
2. Assign the value of `num` to a temporary variable `temp`.
3. Initialize a variable `rev` to 0 (used to store the reversed number).
4. Use a `while` loop to reverse the digits:
   - While `temp > 0`:
     - `rev = (10 * rev) + temp % 10`
     - `temp = temp // 10`
5. After the loop, compare `rev` with `num`:
   - If equal, print that the number is a palindrome.
   - Else, print that it is not a palindrome.

## Program

```
Developed By : Kalpanaa Babu T M
Reg No : 212224230112

num = int(input("Enter a number: "))
temp = num
rev = 0
while temp > 0:
    rev = (10 * rev) + temp % 10
    temp = temp // 10
if rev == num:
    print("Palindrome")
else:
    print("Not Palindrome")
```

## Output

<img width="960" height="172" alt="image" src="https://github.com/user-attachments/assets/a5f66020-4889-44ea-afb6-3804966e8b38" />


<img width="961" height="176" alt="image" src="https://github.com/user-attachments/assets/b90047cd-bdfc-4f09-b377-6d2f30d5339d" />

## Result

Thus the output is executed successfully.
