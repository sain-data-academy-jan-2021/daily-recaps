# Daily Recap (9th Feb)
### Unittesting 3:
- Testing Frameworks
- Mocking
- Patching

---
### In one sentence what is/are:

**Testing Frameworks**
> "A method for automating testing, including a variety of different assertions"
- Pytest and unittest

**Mocking**
> "Creating a fake object to represent a real object during a test"

**Patching**
> "Patching allows you to mock the output you define in another module"

---

### What would you tell yourself when using:

**Testing Frameworks**
- Install testing framework
- Importing library
- Define class (unittest)

**Mocking**
- Input mock data as a variable
- Don't use it if you don't need to
- Import mock & patch specifically (at the top)

**Patching**
- Decorate the test
- Order matters - When decorating patch them in the order they are used in the test, when passing them as an argument reverse this order
- When testing a function that has another dependent function you only patch the function that calls the dependent function