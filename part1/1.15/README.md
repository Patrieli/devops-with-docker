Dockerhub link:

- https://hub.docker.com/r/patrieli/todoplanner

Command to run:

- docker run -p 5000:5000 patrieli/todoplanner

Project GitHub repository:

- https://github.com/Patrieli/ToDoPlanner



Had to change line 10 in run.py in order to get the app served to correct localhost.

app.run(debug=True) -> app.run(host="0.0.0.0" ,debug=True)

