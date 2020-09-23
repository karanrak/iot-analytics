Written by Karan Rakesh - Unity ID : krakesh

The files are provided as a jupyter notebook:
IOT Analytics 2.1
IOT Analytics 2.2

They will generate the output files. Some sample output files have been included but more can be generated and will overwrite these files.

PREREQUISITES:

Prerequisite libraries required to be installed on eos server:

- Install pip
curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
python get-pip.py

- Install jupyter
pip install jupyterlab

- Install pandas
pip install pandas

- Install XlsxWriter
pip install XlsxWriter

RUNNING THE CODE:

To run the code on the eos server and access it locally:

- Follow the section - Access Jupyter Notebook > on Windows 
(https://medium.com/@apbetahouse45/how-to-run-jupyter-notebooks-on-remote-server-part-1-ssh-a2be0232c533) 

Then you can run it by running this command on the eos server
- jupyter notebook --no-browser --port 1234
