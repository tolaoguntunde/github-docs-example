# Writing Good Documentation

## Step 1 - Using Codeblocks.

Codeblocks in markdown make it *very easy* for tech people to **copy, paste, share code**.
A good Cloud Engineer uses codeblocks whenever possible

Because it allows others to copy and paste their codes to replicate or research issue

```
def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n - 1)

# Input a number to calculate its factorial
num = int(input("Enter a number: "))

# Check if the input is a non-negative integer
if num < 0:
    print("Factorial is not defined for negative numbers.")
else:
    result = factorial(num)
    print(f"The factorial of {num} is {result}")
```

```python
def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n - 1)

# Input a number to calculate its factorial
num = int(input("Enter a number: "))

# Check if the input is a non-negative integer
if num < 0:
    print("Factorial is not defined for negative numbers.")
else:
    result = factorial(num)
    print(f"The factorial of {num} is {result}")
```
<img width= "200px" src="https://github.com/tolaoguntunde/github-docs-example/assets/50242126/917e6c00-bbdc-423c-9abb-e633c07f1d1f" />

- Good cloud engineers use codeblocks for botth code and errors that appear in console
```bash
# Define a custom error class
class CustomError(Exception):
    def __init__(self, message):
        super().__init__(message)
```
> Here is an example of using codeblocks for error in bash
> 
## References
- https://learn.cantrill.io/courses/enrolled/1820301
- https://learn.cantrill.io/courses/enrolled/1820301

## Step 3 - Use Github Flavoured Markdown Task Lists

- [x] Dev
- [ ] Staging
- [ ] Prod

## Github extends Markdown allows Emoji
Example is ☁️
- [GitHub Emoji Cheat Sheet](https://github.com/ikatyang/emoji-cheat-sheet)

###click here for more <sup><a href="https://github.com/ikatyang/emoji-cheat-sheet)https://github.com/ikatyang/emoji-cheat-sheet">  [2]  </a></sup>
