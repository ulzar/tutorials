# Reference
 https://www.velotio.com/engineering-blog/grpc-implementation-using-python

# Configuration (only once)
## Create virtualenv (only once)
* Python 2.7
virtualenv venv
* Python 3
virtualenv -p python3 env

## Activate the virtual env
> You need to activate the virtual env whenever you run the server or client (because they rely on grpc packages installed in your virtual env)
source env/bin/activate

## Install libs
1) Activate virtual env
2) Install libs: pip install grpcio grpcio-tools


# Run server
1) Activate virtual env
2) python server.py

# Run client
1) Activate virtual env
2) python client.py