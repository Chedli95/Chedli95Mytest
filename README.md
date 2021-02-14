# Chedli95Mytest
cd Chedli95Mytest/ 
git init
git add *.c
git commit
git clone https://github.com/Chedli95/Chedli95Mytest.git
from random import *
from flask import Flask, render_template, jsonify
import json
import requests

num = randint(10,50)

@app.route('/api/Mytest/')
def Mytest():
  while 10 <= num < 15:
  print(" la valeur est corrcte")
  if num >= 15:
  print ("cette valeur n'est pas correcte")
 return num
 
 app = Flask(__name__)

if __name__ == '__main__':
    app.run()
