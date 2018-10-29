# flask-sse-thread-demo

A server sent event based demo to send data from the server to the clients. Read [this](https://www.smashingmagazine.com/2018/02/sse-websockets-data-flow-http2/) to learn more about SSE and Websockets.  

#### Main Components
* Server side - Flask, Queue, Thread, Gevent
* Client side - JQuery and Materialize

#### Prerequisites 
```
Python >= 3.6
Virtualenv
```

### Installation
Plesase follow the steps below to run the demo.

```
$ git clone git@github.com:cognitiveRobot/flask-sse-thread-demo.git
$ python3 -m venv venv
$ souce venv/bin/activate
$ pip install -r requirments.txt
$ python app.py
```

-- if you find any issue, don't hesitate to raise that. I will reply as early as possible.
