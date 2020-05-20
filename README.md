# Iris Recognition

Iris Recognition is a an application developed using Python. A GUI based iris recognition system made with [PySimpleGUI](https://github.com/pysimplegui). Integrated with MySQL database. 

Customers can register their account, while creating the user account card details will be generated automatically and will be mailed to the customers. They can then login and upload their iris image choosing which part of the eye to be uploaded. Customers can withdraw amount from their account : during the process, users can upload an iris image and compare with their existing image in the database. If the verification was successful payment will be done, else will show error message. (Supported only .BMP images)


#### --------------USERS OF THE SYSTEM------------------
1. Customer :
     
   * Can Register
   * Can Login
   * Deposit Amount
   * Withdraw Amount
   * Upload Iris Image
   * View Transaction Details
   * Visualize Iris Recognition Sequence
2. Admin
   * Can Add Customer
   * Generate ATM Card Details
   * View Customer Details
   * View Transaction Details


## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install foobar.

```bash
pip install PySimpleGUI
pip install mysql-connector
pip install opencv-python
pip install numpy
```

## Usage

```bash
#call the main GUI python file

python main.py
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[Apache](https://choosealicense.com/licenses/apache/)
