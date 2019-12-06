# epydeble

epydeble is a project which goal is to display nearby bluetooth devices on a web page.

## requirements

   - python > 3.6
   - libbluetooth-dev (linux)
   - modules in requirements.txt

## how to

The code currently provides two simple scripts:

	- `scan.py`: scan devices and store them in a json file with their ids, names, and RSSI.
	- `app.py`: simple Flask app

An devices.json file is provided as an example.
The bluetooth code in `blscan` uses PyBluez library.

## for windows 
	PyBluez-win10  instead of bluetooth in scan.py 

## errors 
	errors from path for python on windows couldn't launch virtualenv
	ubuntu VM not responding so we couldn't do the changes we though about

## change we though
	putting a bdd to keep datas instead of using json 
	with the bdd we could have known if a device already got scanned once
	keep also the data of where and when was the device scanned 
	enhance the frontend with flask

## what I understood of Flask
	flask is a web application framework for python, it allows 
	- Contains development server and debugger
	- Integrated support for unit testing
	- RESTful request dispatching
	- Uses Jinja2 templating
	- Support for secure cookies (client side sessions)
	- 100% WSGI 1.0 compliant
	- Unicode-based
	- Extensive documentation
	- Google App Engine compatibility
	- Extensions available to enhance features desired

## to install the project
	require :
	- python3 :    https://www.python.org/downloads/
	- pip : curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py     THEN       python get-pip.py
	- virtualenv  :  pip install virtualenv     
					 virtualenv -p python3 env
					 source env/bin/activate
					 