## Introduction ##

This email address validation function was [originally released](http://www.addedbytes.com/php/email-address-validation/) on [AddedBytes.com](http://www.addedbytes.com/) in June 2004, and was updated following many comments and suggestions from readers.

In July 2008, ICANN announced that the TLD system would be opened up to allow the creation of many many more TLDs, making it more important than ever that email addresses are properly validated according to the standards that define them.

Thus, the script was moved to Google Code ([blog post](http://www.addedbytes.com/blog/email-address-validation-v2/)), to enable easier maintenance and hopefully more people to contribute code. It was originally released under a Creative Commons License, but that has been changed to a BSD license which, among others things, allows commercial use.

## Aims ##

The aim of this project is to create an email address validation class (or function) that checks for technical validity<sup>1</sup> in email addresses, the idea being then that a site can send an email to that address to verify ownership.

1) Certain parts of the standards could be considered security risks and are not in widespread use, so at the time of writing folding white space, control characters and comments are not considered valid by this script.

## Join! ##

The main reason this code has been released under an open source license is to allow others to improve it. Best place to start is probably the [Google Group](http://groups.google.com/group/php-email-address-validation).