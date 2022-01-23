# Module-timer
Function getTimeRemaining calculates the time difference between the indicated date (deadline) and current date (Date.parse(new Date()) in days, hours, minutes, and seconds  

Function setClock creates constants for each of them using the id from an html document and sets timeInterval to update the timer every second

Function updateClock gets the current time difference using the object we had created previously in getTimeRemaining and uses it to update divs

If the total amount of miliseconds gets lower than 0, the timeInterval stops working - which basically stops the timer so that it doesn't get below zero

Function getZero ensures that if the overall number is below 10, the first digit will be zero - just for the user-friendly interface


Using this code, we need to import the module to the main js file and set the selector tied to the HTML document with related id's and set the deadline (e.g. '2022-05-11')
