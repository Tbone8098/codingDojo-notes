# Routes

## Goals
- [ ] What is a route?
- [ ] Why are routes important?
- [ ] Where will we put routes?
- [ ] How do we make this happen?

**Define**: a pathway for data

## HTTP Request Response Cycle
1. Client -> server
2. Server -> database || server -> client
3. Database -> server

### Server.py
```py
from flask import Flask  # Import Flask to allow us to create our app
app = Flask(__name__)    # Create a new instance of the Flask class called "app"


if __name__=="__main__":   # Ensure this file is being run directly and not from a different module
    app.run(debug=True)    # Run the app in debug mode
```