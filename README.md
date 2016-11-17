# OCBCAPI
# Run_ocbcAPI

# Hi 
# I am interested to learn more about python coding and would like to learn how to extract data using OCBC API connection.

$ git clone https://github.com/connect2ocbc/pyocbc.git && cd pyocbcpython setup.py install
$ python setup.py install

import ocbc
forex = ocbc.Forex("https://api.ocbc.com:8243/Forex/1.0", "<TOKEN>")
for rate in forex.all():
    print rate
