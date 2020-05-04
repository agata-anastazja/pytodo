Prerequisites

to run this you need to insert a new connection string that connects to your local database following the pattern:
'postgresql://my_user:my_password@localhost:portNumber/nameOfDB'

To run locally

```
FLASK_APP=app.py FLASK_DEBUG=true flask run
```
