# Password Generator

**Objective:** Create a password generator that produces secure, high-quality passwords suitable for use in authentication systems.

You may define the method signature, but the generator should return a string containing the generated password.

## Requirements

The password generation method must accept the following options:

- `length` (integer) - length of the generated password
- `uppercase` (boolean) - include one or more uppercase `A-Z` characters
- `lowercase` (boolean) - include one or more lowercase `a-z` characters
- `number` (integer) - exact number of numeric `0-9` characters
- `special` (integer) - exact number of special `@%!?*^&` characters

The method should raise an error if the options are invalid (e.g. if the total number of required characters exceeds the specified length).

## Constraints

- Passwords should be generated in a way that ensures high entropy and unpredictability.
- You may use any classes or modules available in the standard Ruby library.
- External libraries may be used for testing purposes only. Do not use them to generate passwords.

## Deliverables

- A Ruby module or library that could be reused in other applications.
- A test suite that demonstrates the correctness and robustness of your solution.
- Documentation including:
 - Basic usage instructions
 - A brief explanation of your approach
 - Any considerations or challenges you encountered

 ## Submission

Push your code into a private repository on GitHub and invite 
[@js1300](https://github.com/js1300) and [@jpswade](https://github.com/jpswade) with read access.
