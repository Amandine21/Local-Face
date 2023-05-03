# Local Face
This repository containts the code and instructions to use a Facial Detection lock system known as "Local Face". This system will require a camera to idenify users and a computer to run a facial detection script. The script will make the decisision to see if the user is valid, and if so it will automatically unlock and electronic door lock. This lock system uses OpenCV Libarary and doese not require any internet connection since it's a local system. This product is open source for the public to use,

The creators of this product are Elvis Hedary, Garret Van Etten, Alexander Hanks, Carlos Zapata III, Alex Warren, and Irene Masabarakiza

1. Add `.jpg` photos of valid users to the `valid_photoID` repository.
2. Modify the python dictionary in the `Detect.py` files to add a single dictionary entry for each user. Be sure to include the working directory path to the user photo/photos. Including multiple photos can increase detection reliability.

## Running the Program

### Raspberry Pi

1. Run `pip install -r piREQ.txt` or `pip3 install -r piREQ.txt` depending on your version of pip.
2. Run `python3 piDetect.py`.

### Mac

1. Run `pip install -r macREQ.txt` or `pip3 install -r macREQ.txt` depending on your version of pip.
2. Run `python3 piDetect.py`.
