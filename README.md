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
  print(" la valeur est correcte")
  if num >= 15:
  print ("cette valeur n'est pas correcte, il faut donner une valeur entre 10 et 15")
 return num
 
 app = Flask(__name__)

if __name__ == '__main__':
    app.run()
