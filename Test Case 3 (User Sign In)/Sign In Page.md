## 3. Test Case 3 (User Sign In)

Registered users should be able to successfully go through the Sign In process. They should be able to sign in using
Email and Password.

## Registered users

## TC1: Successful login with valid details.
.

| **Test Case ID** | **Prequisites** | **Title/Description** | **Steps** | **Expected Result** | **Pass/Fail** |
|------------------|-----------------|------------------------|-----------|----------------------|---------------|
| TC3-1            |Registered users| Confirm that a registered user can successfully log into the system using a valid usename and password. | 1.Open the application.<br>2.Enter a valid Email "koko@roco1.bg" and Password "123456" of a registered user.<br>Click on "SIGN IN" button. |The user is successfully logged in and redirected to the home page.|Pass         |

## TC2: Login with invalid data - Email.

| **Test Case ID** | **Prequisites** | **Title/Description** | **Steps** | **Expected Result** | **Pass/Fail** |
|------------------|-----------------|------------------------|-----------|----------------------|---------------|
| TC3-2            |Registered users| The system does not allow login with an invalid email. | 1.Open the application.<br>2.Enter a invalid Email "koko@roc.bg" and Password "123456" of a registered user.<br>Click on "SIGN IN" button. |The system displays an error message-Unable to sign in.|Pass         |

## TC3: Login with invalid data - Password.

| **Test Case ID** | **Prequisites** | **Title/Description** | **Steps** | **Expected Result** | **Pass/Fail** |
|------------------|-----------------|------------------------|-----------|----------------------|---------------|
| TC3-3            |Registered users| The system does not allow login with an invalid Password. | 1.Open the application.<br>2.Enter a valid Email "koko@roco1.bg" and Password "123456a" of a registered user.<br>Click on "SIGN IN" button. |The system displays an error message-Unable to sign in.|Pass         |

## TC4:  Mismatch between Username and Password.

| **Test Case ID** | **Prequisites** | **Title/Description** | **Steps** | **Expected Result** | **Pass/Fail** |
|------------------|-----------------|------------------------|-----------|----------------------|---------------|
| TC3-4            |Registered users| To confirm that the system does not allow login if the entered username and password do not match.. | 1.Open the application.<br>2.Enter a valid username and password, but ones that do not match.<br>Click on "SIGN IN" button. |The system displays an error message stating that the entered username and password do not match, and it does not allow the user to log in.|Pass         |

## TC5: Remember Password" Checkbox.

| **Test Case ID** | **Prequisites** | **Title/Description** | **Steps** | **Expected Result** | **Pass/Fail** |
|------------------|-----------------|------------------------|-----------|----------------------|---------------|
| TC3-5            |Registered users| To verify the proper functionality of the "Remember Password" checkbox on the login page.. |1.Initial State of the Checkbox<br>Текст с черна точка: •Action: Check the initial state of the "Remember Password" checkbox.<br>Текст с черна точка: •Expected Result: The checkbox is not checked by default.<br>2.Check "Remember Password":<br>Текст с черна точка: •Action: Enter valid login credentials and check the "Remember Password" checkbox.<br>Текст с черна точка: •Expected Result: The checkbox can be successfully checked. No error is displayed.<br>3.Login with Remembered Password:<br>Текст с черна точка: •Action: Log in with the previously checked "Remember Password" option.<br>Текст с черна точка: •Expected Result: The system successfully logs in the user, and the password is pre-filled if the "Remember Password" option was checked.<br>4.Uncheck "Remember Password":<br>Текст с черна точка: •Action: Log out and log in again, unchecking the "Remember Password" checkbox.<br>Текст с черна точка: •Expected Result: The system successfully logs in the user, but the password is not remembered or pre-filled.<br>5.Invalid Login Attempt with "Remember Password" Checked:<br>Текст с черна точка: •Action: Attempt to log in with invalid credentials while the "Remember Password" checkbox is checked.<br>Текст с черна точка: •Expected Result: The system does not remember the invalid credentials, and the checkbox status remains unchanged. |The "Remember Password" checkbox has been tested for its default state, functionality, and interaction with login attempts.The "Remember Password" checkbox works correctly, toggling as expected according to user actions and not causing errors during login.|Pass         |


