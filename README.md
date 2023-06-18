# Desiree's App

Just a sample flask app (which is a python backend).

## Instructions

1.  install pip (python package manager) -- Run these commands

`curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py`

`python get-pip.py`

2.  Install flask

`pip install flask`

3. Run app

`python main.py`

4.  Load App in Browser

`http://localhost:8080/`

## Coding

Flask uses Jinja which is a templating language in python.  The {{ }} stuff in the index.html file is jinja doing a for loop over the data loaded from data.json, which is injected during the render in the index function.  You can add items and stuff to data.json, and they will appear on reload.  The top part is just some sample bootstrap that I threw in there.  Bootstrap is a css framework that has built in classes for html to look pretty.

