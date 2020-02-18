# basic-dash-auth-flow
Basic auth for Dash using the Flask session object

The main layout content is a function wrapped by a decorator that checks whether the user has a current session. If not, it returns an unauthorized error page instead of the main layout content.

```bash
git clone https://github.com/russellromney/basic-dash-auth-flow
cd basic-dash-auth-flow
python app.py
```

![UI](ui.gif)
