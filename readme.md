To run this application pip install the following packages:
flask
flask_cors
pandas

then run the command 'python app.py'

This backend is setup with the flask package and uses a postgres database

There are 4 api requests including:
GET /ma-schools -> This gets the entire list of colleges

GET /ma-schools/<name>  -> This gets one of the colleges based on the college name with dashes in between (ex: "university-of-massachusetts)

GET /fields -> This gets all the fields related to each college

GET /programs -> This gets all the programs details related to the college offered programs

The frontend is located at https://collegesearchfrontend.herokuapp.com/