# REST

To make an update :
go to https://sheltered-hollows-39392.herokuapp.com/submit

To retrieve the details for a particular date and room type use the following url with the specified query string parameters
https://sheltered-hollows-39392.herokuapp.com/detail?date=<date in YYYY-MM-DD format>&type=<"single" or "double">
for example
https://sheltered-hollows-39392.herokuapp.com/detail?start=2018-05-21&type=single


To run locally
1.Install virtualenv for python
2.Run the following commands
	1.virtualenv env
	2.source env/bin/activate
	3.pip install requirements.txt
	4.python app.py
