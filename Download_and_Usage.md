## Download ##

To download the email address validation code, click on "Source" above, and follow the instructions in that section.

You will be able to download the most recent (or any previous) version of the code from the "trunk" folder of the repository using Subversion. If you don't have Subversion, you can use the source browser to grab the code instead.

A unit test class can be found in the "tests" folder.


## Example Usage ##

```
include('EmailAddressValidator.php');
$validator = new EmailAddressValidator;
if ($validator->check_email_address('test@example.org')) { 
    // Email address is technically valid 
} else {
    // Email not valid
}
```