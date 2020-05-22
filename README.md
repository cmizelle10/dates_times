# dates_times
date and times base R
Formatting symbols:
* %Y: 4-digit year (1982)
* %y: 2-digit year (82)
* %m: 2-digit month (01)
* %d: 2-digit day of the month (13)
* %A: weekday (Wednesday)
* %a: abbreviated weekday (Wed)
* %B: month (January)
* %b: abbreviated month (Jan)

Similar to working with dates, you can use as.POSIXct() to convert from a character string to a POSIXct object, and format() to convert from a POSIXct object to a character string. Again, you have a wide variety of symbols:

* %H: hours as a decimal number (00-23)
* %I: hours as a decimal number (01-12)
* %M: minutes as a decimal number
* %S: seconds as a decimal number
* %T: shorthand notation for the typical format %H:%M:%S
* %p: AM/PM indicator
For a full list of conversion symbols, consult the strptime documentation in the console:

?strptime
