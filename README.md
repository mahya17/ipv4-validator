# IPv4 Validator 🔢

A Python program that checks whether an IPv4 address is valid.

## About the Project

I built this project as part of **CS50's Introduction to Programming with Python** by Harvard University.

The program takes an IPv4 address as input and checks whether it follows the correct format. Each part of the address must be a number between `0` and `255`.

The project also includes tests to check the `validate` function with both valid and invalid IPv4 addresses.

## How It Works

The program asks the user to enter an IPv4 address and uses the `validate` function to check it.

For example:

```text
IPv4 Address: 127.0.0.1
True
```

An invalid address returns:

```text
IPv4 Address: 512.512.512.512
False
```

## What I Practiced

While working on this project, I practiced:

* Regular expressions
* Using the `re` module
* Validating user input
* Working with `re.search()`
* Capturing groups
* Writing unit tests with `pytest`
* Testing valid and invalid inputs

## Technologies

* Python
* Regular Expressions
* pytest

## Testing

The project includes a separate test file for checking the `validate` function.

Run the tests with:

```bash
pytest test_numb3rs.py
```

## Course

This project was completed as part of **CS50's Introduction to Programming with Python** by Harvard University.
