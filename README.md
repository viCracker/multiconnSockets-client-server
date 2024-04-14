# viCracker Multiconnection Client and server(Sockets)
This is an improvement of my <a href="https://github.com/viCracker/echo-client-server">EchoProject</a> which allows for multiple connections from
the client to the server.
# Usage
You need to run each script on a seperate command line instance
On the server's sript issue the host and ip you need the server to run on.
Uhhm!, lets assume you are using localhost.
Run: <br> <code>python multiconn-server.py 127.0.0.1 65432</code><br>
You could replace the arguments: 127.0.0.1 and 65432 with any ip and port where you want your server to run on
On the second instance launch the client's script and issue arguments: <i>host</i>, <i>port</i> and <i>number of connections</i>.
<i>host</i>, <i>port</i> are the ip and ready-port of the server. <br>
<code>python multiconn-client.py 127.0.0.1 65432 2</code><br>
<strong>Now! Watch the magic</strong>
# Disclaimer
For security purposes experiment with your Network's loopback interface(localhost). <br>
If you are hacked I am not responsible. <br>
For educational purposes only, I do not take responsibility for any unauthorized/unethical/illegal use of this shit.
