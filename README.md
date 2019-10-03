###Create User Id

###(String Handling)

Create user_id by accepting first_name, last_name and pin_
code from user by using Scanner class.
```
Stirng firstName;
String lastName;
int pincode;
```
Create user_id on the basis of following conditions:
1. Take first two characters of the greater string and Take last two characters of the smaller string, of two given
strings firstName & lastName.

2. Traverse the pin code in forward direction and take the digit at the position given by greater string length.
If greater string length is more than number of digits take the last digit.

3. Traverse the pin code in the reverse direction and take the digit at the position given by smaller string length.
If smaller string length is more than number of digits take the first digit.

4. if the two string are similar consider ``` String greater = lastName;
String smaller = firstName;```
