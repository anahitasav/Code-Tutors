# Team Dragonfly Group project

## Team members
The members of the team are:
- Anahita Savarypour
- Juri Alaskar
- Ahmed Almuallem
- John Paul San Diego

## Project structure
The project is called `code_tutors`.  It currently consists of a single app `tutorials`.

## Installation instructions
To install the software and use it in your local development environment, you must first set up and activate a local development environment.  From the root of the project:

```
$ virtualenv venv
$ source venv/bin/activate
```

Install all required packages:

```
$ pip3 install -r requirements.txt
```

Migrate the database:

```
$ python3 manage.py migrate
```

Seed the development database with:

```
$ python3 manage.py seed
```

Run all tests with:
```
$ python3 manage.py test
```

*The above instructions should work in your version of the application.  If there are deviations, declare those here in bold.  Otherwise, remove this line.*

## Sources
The packages used by this application are specified in `requirements.txt`

## Disclosure of AI Assistance
We utilized OpenAI's ChatGPT to assist in generating some of the test cases for the application. The AI tool provided initial test case structures, which we then validated and implemented by ourselves to ensure their effectiveness and alignment with the project objectives.

