# basic-dash-auth-flow
Basic auth for Dash using the Flask session object

The main layout content is a function wrapped by a decorator that checks whether the user has a current session. If not, it returns an unauthorized error page instead of the main layout content.

```bash
git clone https://github.com/russellromney/basic-dash-auth-flow
cd basic-dash-auth-flow
python app.py
```

![UI](ui.gif)


### Code

`server.py`: create the app object

`app.py`: build layout items, callback functions, and run the app

`auth.py`: create the authentication decorator, user authentication function, and dict of users/passwords
