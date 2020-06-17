# Document-classification-Problem-

Approach:

1.Setup a EC2 cluster on AWS and connect it to local directory using commands
$ sudo chown -v user keyValuePair.pem 
$ chmod 400 keyValuePair.pem 
$ ssh -i keyValuePair.pem

2.Setup an Python3 environment
$ sudo pip install python3
$ pip3 install virtualenv 
$ pip3 install Flask

3.Upload files to EC2 via Filezilla
Drag and drop all the relevant files like DocC.ipynb, Model_api.py and other view file to EC2 cluster
Install Numpy, Pandas , NLTK in order to run the model_api.py

4.Run the model_api.py after Installing all the Requirements.

