# Personalized Greeting Program

This is a simple Python program that collects user input for their name, age, and location, then displays a personalized greeting message.

## Features

- **Interactive User Input**: Prompts the user to enter their name, age, and location.
- **Custom Greeting**: Provides a friendly, tailored message based on the user's responses.

## How to Run

1. **Clone the repository** (or copy the code into a Python file on your machine):
    ```bash
    git clone https://github.com/yourusername/personalized-greeting-program.git
    ```
2. **Navigate to the directory**:
    ```bash
    cd personalized-greeting-program
    ```
3. **Run the program**:
    ```bash
    python user_input.py
    ```

## Code

Here’s the main script (`greeting.py`):

```python
# Ask for user's information
name = input("What's your name? ")
age = input("How old are you? ")
location = input("Where are you from? ")

# Print a personalized message
print(f"Hello, {name}! It's great to meet someone who is {age} years old from {location}. Hope you're having a fantastic day!")
```

## Example Usage

When you run the program, it will ask for your name, age, and location:

```bash
What's your name? Alice
How old are you? 25
Where are you from? New York
```

### Output

The program will respond with a personalized greeting:

```bash
Hello, Alice! It's great to meet someone who is 25 years old from New York. Hope you're having a fantastic day!
```
