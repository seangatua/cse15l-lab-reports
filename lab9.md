**SEAN GATUA**\

**INITIAL ERROR**\

![Image](cd(lab9bugssymptoms.png)

I had a question about my code. I'm trying to write a program that returns the fractional part of a decimal. Right now, my tests are failing and I've rechecked my code multiplle times and still can't understand why this is happening.

Hi (so,so), have you tried using print statements for your original function? Or possibly tried jdb to see what is happening underneath the hood?

**COMMAND LINE OUTPUTS**\


![Image](cd(lab9Error1.png)
![Image](cd(lab9Error2.png)


Instead of returning the fractional portion, I've programed the function to return the difference of decimal portion and the fractional.\
That is why the function returns a double value with whole digits instead of a double value less than or equal to 0.\

