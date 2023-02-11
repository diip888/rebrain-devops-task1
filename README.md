<h1 align="center">Hi there, I'm <a href="http://195.122.251.157/" target="_blank">Dmitry </a>
<img src="https://github.com/blackcater/blackcater/raw/main/images/Hi.gif" height="32"/></h1>
<h3 align="center"> DevOps student <a  href="https://rebrainme.com" target="_blank">Rebrain </a> school , from Russia 🇷🇺</h3>

<!---Running string-->
[![Typing SVG](https://readme-typing-svg.herokuapp.com?color=%2336BCF7&lines=Wow!+Come+on!+I`ll+ride!)](https://git.io/typing-svg)

![PowerShell Gallery](https://img.shields.io/powershellgallery/dt/Azure)

# Repository description in README.md

The project __as if__ is a digital solution within the framework of the World AI&DATA Challenge, corresponding to the task <https://git.asi.ru/tasks/world-ai-and-data-challenge/>

Проект __как бы__ является цифровым решением в рамках конкурса World AI&DATA Challenge, соответствующиим задаче  <https://git.asi.ru/tasks/world-ai-and-data-challenge/>

## Getting Started __like__

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See *deployment* for notes on how to deploy the project on a live system.

### Prerequisites __like__

What things you need to install the software and how to install them:

```bash
uname -a # test you linux core
apt update
apt upgrade -y
```

### Installing __like__

A step by step series of examples that tell you how to get a development env running

```bash
mkdir pytest_project
cd pytest_project
python3 -m venv pytest-env
```

```bash
source pytest-env/bin/activate
pytest --pyargs mypkg
```

And repeat

```text
until finished
```

End with an example of getting some data out of the system or using it for a little demo

## Running the tests __like__

Explain how to run the automated tests for this system.
Test automation pyramid consists of three levels:

1. Unit Tests

    1.1 Subunit test

2. Integration Tests

3. End to end Tests

I didn't know how make automated tests. But i'll learn it to rebrain  <a  href="https://rebrainme.com" target="_blank">Rebrain </a> courses.

```python
def test_sum():
    assert sum([1, 2, 3]) == 6, "Should be 6"

if __name__ == "__main__":
    test_sum()
    print("Everything passed")
```

* [X] check

### Break down into end to end tests __like__

End to end testing (E2E testing) is a software testing method that involves testing an application’s workflow from beginning to end. This method aims to replicate real user scenarios to validate the system for integration and data integrity.

```python
Traceback (most recent call last):
  File "test_sum_2.py", line 9, in <module>
    test_sum_tuple()
  File "test_sum_2.py", line 5, in test_sum_tuple
    assert sum((1, 2, 2)) == 6, "Should be 6"
AssertionError: Should be 6
```

### And coding style tests __as is__

We will also write a test, test_capital_case to ensure that the function does what it says. We’ll prefix our test function names with test_, since this is what pytest expects our test functions to be named.

```python
# test_capitalize.py

def capital_case(x):
    return x.capitalize()

def test_capital_case():
    assert capital_case('semaphore') == 'Semaphore'

```

## Deployment  __like__

Add additional notes about how to deploy this on a live system

## Built With

|- [Billie Thompsom](https://github.com/PurpleBooth)| 
|- [Maven](https://maven.apache.org/) - Dependency Management|
|- [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds|

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

| Version | Description change |
| :---------: | :------- |
| v0.9 | added file .gitignore with .cedit   |
| v0.8 |  changes README.md ver1.1    |
| v0.6 | i changed README , added refer http rebrain |
| v0.5 |  i added Readme-template.md from PurpleBooth |
| v0.4 |   3th chande README.md |
| v0.3 |    2 change README.md |
| v0.2 |     first change README.me |
| v0.1 |      i comited file nginx.conf · 6 days ago |


## Authors

- __Dmitry__ [diip888](https://gitlab.rebrainme.com/devops_users_repos/4762/rebrain-devops-task1)


- __Billie Thompson__ - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)

## Acknowledgments

- Hat tip to anyone whose code was used
- Inspiration
- etc
- __like__ = как бы
