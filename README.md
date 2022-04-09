# credit-card-web-application

Functional Overview:
This application allows to perform Create/Read operations. 

Users can add new Credit Cards to the System and each credit card has 3 attributes: User Name, Card Number, withdrawal Limit. The User will then be able to view the added credit cards as a list in a table.

This Application allows to insert 16 to 19 digit card numbers and also allows users to write such numbers in full or by writing the digits separated by spaces or dashes. It will be then the App to elaborate and format the card's numbers. All the Card Numbers must work against the Luhn 10 algorithm, otherwise validation errors will be displayed.

The Luhn 10 algorithm has been implemented on both front-end and back-end to provide a more secure application.

Front-end Technologies:
Javascript, ReactJs,  Ajax Jquery, CSS

Validation:

1. All input and output are JSON.
2. Credit card numbers may vary in length, up to 19 characters 
3. Credit card numbers will always be numeric.
4. Hand coded Luhn 10 check has been implemented.
