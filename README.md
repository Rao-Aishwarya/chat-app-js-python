# chat-app-js-python

This is code mainly focuses on the backend aspect of the application. The code and the instructions for the frontend can be found here 👇

https://github.com/alamorre/js-chat-website

Run the following commands to have a working python code

Create a backend folder
```
mkdir backend
cd backend
```

Setup a virtual environment to hold all the necessary dependencies
```
python3 -m venv venv
source venv/bin/activate
```

Install the following dependencies:
1. fastapi (our server framework)
2. uvicorn (to run our server)
3. requests (to make API calls to Chat Engine later)

```
pip install --upgrade pip
pip install fastapi "uvicorn[standard]" requests
pip freeze > requirements.txt
```

And lastly run the server
```
uvicorn main:app --reload --port 3001
```
