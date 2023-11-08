# CODING

<!DOCTYPE html>
<html>
<head>
<title>Page Title</title>
</head>
<body>

<h1>This is Maxwell Rubert</h1>
<p>I'm from Kanyakumari, I am glad to learn front end development rn!</p>
<b>Maxwell Rubrt</b>

</body>
</html>

python
def is_palindrome(input_str):
    # Remove spaces and convert to lowercase
    input_str = input_str.replace(" ", "").lower()
    # Check if the string is equal to its reverse
    return input_str == input_str[::-1]

# Get user input
user_input = input("Enter a string: ")

# Check if it's a palindrome and print the result
if is_palindrome(user_input):
    print("It's a palindrome!")
else:
    print("It's not a palindrome.")
