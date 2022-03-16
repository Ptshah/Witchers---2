# Witchers---2

| Test Category | Test Category | Test case description | Test steps | Expected result | Prerequisites | Executed by | Pass/Fail |
| --- | --- | --- | --- | --- | --- | --- | --- |
| UX 1 | UX 1.1 | Valid username and valid password | Enter a valid Username, password and click on login button. | Successful login | Valid Url  and browser | Preet | Pass |
|  | UX 1.2 | Valid username and invalid password | Enter a valid Username, invalid password and click on login button. | A pop-up message box to show invalid username/password. | Valid Url  and browser | Preet | Pass |
|  | UX 1.3 | Invalid username and valid password | Enter Invalid username and valid password  | A pop-up message box to show invalid username/password. | A pop-up message box to show invalid username/password. | Preet | Pass |
|  | UX 1.4 | Invalid username and valid password | Enter Invalid username and valid password  | A pop-up message box to show invalid username/password. | A pop-up message box to show invalid username/password. | Preet | Pass |
|  | UX 1.5 | Blank field for username and valid password | Enter Invalid username and valid password  | A pop-up message box to show invalid username/password. | A pop-up message box to show invalid username/password. | Preet | Pass |
|  | UX 1.6 | Valid  username and blank field for password | Enter Invalid username and valid password  | A pop-up message box to show invalid username/password. | Valid Url  and browser | Preet | Pass |
|  | UX 1.7 | Blank field for username and  password | Leave both blank and press login button.  | A pop-up message box to show invalid username/password. | Valid Url  and browser |  |  |
| UX 2 | UX 2.1 | By clicking  the sign up it should land him to another page for signing up | Click the sign up button below the login fields  | It should direct you to the sign up page  | Valid Url  and browser |  |  |
|  | UX 2.2 | Incorrect form  of user id | Username should be atleast 8 string long and no space included.  | If incorrect combination is entered than an appropriate message is generated.  | Valid Url  and browser |  |  |
|  | UX 2.3 | Incorrect form of password. | Password should not have spcaes and  atleast 8 character long , One upper case, one lower case, one special character.  | If the password is not entered in correct form display message password contain atleast 8 char ,one upper,lower,special character required.  | Valid Url  and browser |  |  |
|  | UX 2.4 | Password field and confirmation password field mis matching. | Password and confirmation password field should be mismatched.  | If the password and confirmation password are mismatched display an appropriate message. | Valid Url  and browser |  |  |
|  | UX 2.5 | Form is correctly field out then direct the user to the landing log in page.  | After filling out all the detail on the form correctly , click on the submit button it should navigate to landing log in page.  | Pop up message for successfully signed up.  | Valid Url  and browser |  |  |
| UX 3 | UX 3.1 | Checking the new sign up credentials | Checking the new sign up credentials | Successful login | Valid Url  and browser |  |  |
| DB1 | DB 1.1 | Check whether data gets written  database after succesfull sign up. | Enter valid username and password after successful sign up see whether username  | Database will not be altered. |  |  |  |
| API1 | API 1.1 | Authorised user should sign up succesfully with response code 200. | Enter correct credentials  | Response code is 200 |  |  |  |
|  | API 1.2 | Authorised user enters invalid password , response code 401. | Invalid c redentials  | response code is 401. |  |  |  |
|  | API 1.3 | Valid password and invalid username then response code 401. | Response code is 401 on invalid credentials. | response code is 2401 |  |  |  |



# Testplan
