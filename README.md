
## Setting up the API endpoint
Setting up the server is a fairly straightforward task, here are the steps:

1. Install pip, the python package manager.
2. cd to the directory containing the sentiment code and run `pip install -r requirements.txt` . This will install the dependencies.
3. Install redis and start the program redis-server. Eg: `redis-server --daemonize yes`. 
Redis is used here only for tracking/stats purposes, if you don't want it remove all references to redis in the code.
 
 Run the server by executing the command `nohup python run.py &`
