# Simple-project-using-flask-sql

A simple project which helps you to make your regular ***TODO*** list.

I follow [freecodecamp.org](https://www.youtube.com/watch?v=Z1RJmh_OqeA) for this project

This repo has been updated to work with `Python v3.8` and up.

## How To Run
Install `virtualenv:`
`$ pip install virtualenv`

Open a terminal in the project root directory and run:
`$ virtualenv env`

Then run the command:
`$ .\env\Scripts\activate`

Then install the dependencies:
`$ (env) pip install -r requirements.txt`

Finally start the web server:
`$ (env) python app.py`

This server will start on port 5000 by default. You can change this in app.py by changing the following line to this:

```python
if __name__ == "__main__":
    app.run(debug=True, port=<desired port>)
 ```

