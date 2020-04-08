#Project Class Structure

The core of the entire project is the calculation class

Calculation Class:
Properties Include all variables necessary for calculating a lease payment
One constructor without input setting all properties at default value
One constructor that receives values for all properties

setters for all properties that clients should able to control

updateCalculation is a void method to be used in case the properties have changed without the payment being updated.

calcPayment is a public void function that calculates all aspects of the lease payment and saves the information to the appropriate properties.

getTaxTotal returns the total amount of taxes 

getPayment Function returns the monthly lease payment as a float using all properties
