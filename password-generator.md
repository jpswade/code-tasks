# Password Generator

**Objective:** Create a password generator that can create a cryptographically secure password, 
suitable for use in authentication systems.

It should be possible to generate a password by calling a method—you may choose
the method signature for this. The method should return a string containing the
new password.

## Requirements

This generation method should accept the following options which define the
requirements of returned passwords:

- `length` — (integer) length of the generated password
- `uppercase` — (boolean) include one or more uppercase `A-Z` characters
- `lowercase` — (boolean) include one or more lowercase `a-z` characters
- `number` — (integer) exact number of numeric `0-9` characters
- `special` — (integer) exact number of special `@%!?*^&` characters

The function should produce an error in the event of invalid options.

## Constraints

* Passwords should be generated in a way that ensures high entropy and unpredictability.
* You may use any classes or modules available in the standard Ruby library.
* External libraries may be used for testing purposes only. The core password
  generation logic must be your own implementation. Don't use them to generate passwords.

## Deliverables

* The code should be packaged as a library/module which could be included into
  other libraries and applications.
* Tests should be included to verify that the code works as intended.
* Documentation should be included to demonstrate how to use the library. A well
  written README is more than sufficient. Please add some notes about how you
  approached the problem, and any difficulties or issues you encountered during
  development.

## Submission

Push the library into a private repository on GitHub and invite 
[@js1300](https://github.com/js1300) and [@jpswade](https://github.com/jpswade) with read access.
