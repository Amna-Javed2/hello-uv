## install uv
uv docs ==> Installation ==> command ==> pip install uv


## Initialized or Create a Folder
uv init --package hello-uv


cd hello-uv
code .

## Create a file in the src folder.
hello.py
Write some code or a function in hello.py

## For Example
```python 
def greeting():
    print("Hello World")
```
Define this function or file in pyproject.toml File

## Create Virtual environment
uv venv

## Activate Scripts or code
.venv\Scripts\activate

## Run the code
command ==> uv run hello