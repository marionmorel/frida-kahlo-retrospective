# Frida Kahlo Retrospective Off-Platform Project
## Data Scientist: Analytics - Codecademy

### Overview

This project is slightly different than others you have encountered thus far on Codecademy. Instead of a step-by-step tutorial, this project contains a series of open-ended requirements which describe the project you’ll be building.

There are many possible ways to correctly fulfill all of these requirements, and you should expect to use the internet, Codecademy, and other resources when you encounter a problem that you cannot easily solve.

### Project Goals

Congratulations! You’ve been hired to work on a retrospective of Frida Kahlo’s work at a major museum in Mexico.

Your job is to put together the audio tour, but in order to do that, you need to create a list of each painting featured in the exhibit, the date it was painted, and its spot on the tour.

Use your knowledge of Python lists to create a master list of each painting, its date, and its audio tour ID.

### Tasks

1. First, create a list called paintings and add the following titles to it:

<code>'The Two Fridas'</code>, <code>'My Dress Hangs Here'</code>, <code>'Tree of Hope'</code>, <code>'Self Portrait With Monkeys'</code>

2. Next, create a second list called dates and give it the following values:

<code>1939</code>, <code>1933</code>, <code>1946</code>, <code>1940</code>

3. It doesn’t do much good to have the paintings without their dates, and vice versa. Zip together the two lists so that each painting is paired with its date and resave it to the paintings variable. Make sure to convert the zipped object into a list using the <code>list()</code> function. Print the results to the terminal to check your work.

4. There were some last minute additions to the show that we need to add to our list. Append the following <code>paintings</code> to our paintings list then re-print to check they were added correctly:

* <code>'The Broken Column'</code>, <code>1944</code>
* <code>'The Wounded Deer'</code>, <code>1946</code>
* <code>'Me and My Doll'</code>, <code>1937</code>

5.Since each of these paintings is going to be in the audio tour, they each need a unique identification number. But before we assign them a number, we first need to check how many paintings there are in total.

Find the length of the <code>paintings</code> list.

6. Use the <code>range</code> method to generate a list of identification numbers that starts at 1 and is equal in length to our list of items. Save the list to the variable <code>audio_tour_number</code> and check your work by printing the list.

7. We’re finally ready to create our master list. Zip the <code>audio_tour_number</code> list to the <code>paintings</code> list and save it as <code>master_list</code>.

8. Print the <code>master_list</code> to the terminal.