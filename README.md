qsms
====

A bash script for sending SMS messages from your Jolla phone

Put the file into /usr/local/bin.
Make sure that it is executable.

When logged in via ssh, running:

    qsms "This is a message" "123 456 7890"
   
Will send the SMS message "This is a message" to phone 123 456 7890.

You can have "+" at the begining of the phone number and spaces in it. Letters are not allowed.

If you put multiple numbers in the list, the same message will be sent to all of the numbers.

Don't be nasty, don't use this for spamming please.
