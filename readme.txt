This is a port of the china-daily-email project (https://github.com/mwweinberg/china-daily-email) because that repo is full of all sorts of random bits of stuff I used to figure out how to build it and therefore has become hard to follow.

china-daily-email.py is the primary script. 

input.csv is the input file to run the script.  It requires that each URL be paired with the appropriate letter code for the category of story associated with the URL.

template_first_half.html is the first part of the email template from mailchimp.

template_second_half.html is the second part of the email template from mailchimp.

adder.py is the mini script used to test out new scrapers.  use adder.csv to import the target URL.  Once you have something that works you can add it to the headliner() function by replicating it 3 times (for a total of 4) and changing the letter in both the "code ==" section at the top of the blob and the "holder_cat_" section towards the end.
