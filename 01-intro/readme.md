#the flask app basic template
from flask import Flask, render_template, request, redirect, url_for
import os

app = Flask(__name__) #create a flask app
#view function 
//represents a html page

# "magic code" -- boilerplate
if __name__ == '__main__':
    app.run(host=os.environ.get('IP'),
            port=int(os.environ.get('PORT')),
            debug=True)
