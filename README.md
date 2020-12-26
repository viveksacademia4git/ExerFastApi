# Exercise Fast API

Library: [Fast API](https://fastapi.tiangolo.com)

This project is created for learning and implementing the Fast API in Python.


### Setup Environment

- Installation:
   - `pip3 install fastapi[all]` or `pip install fastapi[all]`
   - `pip3 install pytest` or `pip install pytest`


### Project Execution

Execute the '[main_controller](main/program/controller/main_controller.py)' using command:
`uvicorn main.program.controller.main_controller:app --reload`

URLS:
 - Interactive API docs: http://127.0.0.1:8000/docs
 - Alternative API docs: http://127.0.0.1:8000/redoc


### Test Execution

Execute tests using command:
`python3 -m pytest`