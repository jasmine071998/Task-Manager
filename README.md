**Task Manager App**

This is a simple Task Manager App developed using Flask. 

**Steps to run**

1) Install virtualenv:
$ pip install virtualenv

2) Open a terminal in the project root directory and run:
$ virtualenv env

3) Then run the command:
$ .\env\Scripts\activate

4) Then install the dependencies:
$ (env) pip install -r requirements.txt

5) Finally start the web server:
$ (env) python app.py

6) This server will start on port 5000 by default. You can change this in app.py by changing the following line to this:

if __name__ == "__main__":
    app.run(debug=True, port=<desired port>)  
 
