# Accessing-data-in-API-through-JSON
The above code performs various functions.
1. getLatestRates-This function returns a JSON string that is a response to a latest rates query.

2.changeBase-This function takes amount, and the currency in which is amount is and converts the given amount of the currency into a currenct inputted by the user according to the rates on a given date.

3.printAscending-This function prints the latest rates of the currencies in a sorted order.

4.extremeFridays-It is a function that takes a starting and the ending dates and a given currency. It returns the fridays on which the currency was the weekest and strongest.

5.findMissingDates- In the data, data for certain dates is missing.This functions takes the start and the end date and returns the dates whose data is not present.

These functions access data from https://exchangeratesapi.io/
