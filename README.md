https://sudarshan34.github.io/DigiClock/

I have used updateClock function is defined. Inside this function,it creates a new Date object representing the current date and time and
It retrieves the current hours, minutes, and seconds using the getHours, getMinutes, and getSeconds methods of the Date object. These values are converted to strings with zeros if needed to ensure they 
always have two digits and It updates the content of HTML elements with IDs hours, minutes, and seconds with the respective values.The updateClock function is immediately called once to set the initial time.
The setInterval function is used to repeatedly call the updateClock function every 1000 milliseconds (1 second). This ensures that the displayed time is updated in real-time.
