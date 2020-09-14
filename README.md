# Team_Generator

Building a Node CLI that takes in information about employees and generates an HTML webpage that displays summaries for each person. I will also be ensure that all unit tests pass.

## Classes

The project has these classes: `Employee`, `Manager`, `Engineer`,`Intern`.
The first class is an `Employee` parent class with the following properties and methods:

- name
- id
- email
- getName()
- getId()
- getEmail()
- getRole() // Returns 'Employee'

The other three classes extend `Employee`.

In addition to `Employee`'s properties and methods, `Manager` has:

- officeNumber

- getRole() // Overridden to return 'Manager'

In addition to `Employee`'s properties and methods, `Engineer` has:

- github // GitHub username

- getGithub()

- getRole() // Overridden to return 'Engineer'

In addition to `Employee`'s properties and methods, `Intern` has:

- school

- getSchool()

- getRole() // Overridden to return 'Intern'

## Application
