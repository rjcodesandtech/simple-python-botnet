# simple-python-botnet
A simple botnet implementation using Python. It has a server program which store, send and update code payload for client machine and the client program which fetch the codes from the server. It uses the exec() function of Python to perform specific functionalities.
# Note
This program is for educational purposes only. Using this in unethical ways is punishable by your national laws and regulation.
# Setup
For the server side, make sure that Flask is installed in your server and simply run the wsgi.py and make sure that the port 8080 isn't occupied by other program or you will change the port number with available port (Flask default is 5000).
For client side, first install the pyinstaller on your deployment machine to create .exe file then simply distribute the .exe to target machine.
# Requirements
Server side
Flask
Client side (deployment machine)
pyinstaller
