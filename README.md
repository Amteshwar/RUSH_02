# RUSH_02

Our idea was to copy the entire dictionry into a strucy array
We split each line into two
The first was the number and the second was the word
Foe example. 0: zero
So "0" and "zero" was the only thing we wanted
We did this by cycling through the file and using the colon (:) and the newline character (\n) at the end to split the line
Then we stored both into a struct array which linked the number to the english work
Side note. We also did Malay but more on that later

We took the characters that the user inputed and converted it into unsigned integers
But we didnt just convert it into a number
We converted it into a array.
So "1456" was converted into [1, 4, 5, 6] all as unsigned int

Then we converted that int into an array with the placeholders that we can then translate
Folowing our example [1, 4, 5, 6] become [1, 1000, 4, 100, 50, 6]
This way we can directly traslate using our struct array

After getting back the array we traslated it using a few english rules
So the final result was one thousand, four hundred and fifty-six.

This was the idea but we had a few problems namely with zero's as our fuctions just removed all zeros
Also the incomtablity to go from an array to pointer also made our find fuction not work.
These are a few problems but there are more which we will discuss in person tommorow

Thanks for agreeing to look into our code
muhbin-m's team
