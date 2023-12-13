## 3. Test Case 3 (User Sign In)

Registered users should be able to successfully go through the Sign In process. They should be able to sign in using
Email and Password.

## Registered users

## TC1: Successful login with valid details.


| **Test Case ID** | **Prequisites** | **Title/Description** | **Steps** | **Expected Result** | **Pass/Fail** |
|------------------|-----------------|------------------------|-----------|----------------------|---------------|
| TC3-1            |The user has valid login credentials (username and password) for the application.| Verify successful login with valid details. | 1.Open the application.<br>2.Enter a valid Email "koko@roco1.bg" and Password "123456" of a registered user.<br>Click on "SIGN IN" button. |The system should successfully authenticate the user, and the user should be redirected to the home page/dashboard.|Pass         |

## TC2: Login with invalid data - Email.

| **Test Case ID** | **Prequisites** | **Title/Description** | **Steps** | **Expected Result** | **Pass/Fail** |
|------------------|-----------------|------------------------|-----------|----------------------|---------------|
| TC3-2            |The user has invalid login credentials (invalid email or email format).| Verify login with invalid data - Email. | 1.Open the application.<br>2.Enter a invalid Email "koko@roc.bg" and Password "123456" of a registered user.<br>Click on "SIGN IN" button. |The system displays an error message-Unable to sign in.|Pass         |

## TC3: Login with invalid data - Password.

| **Test Case ID** | **Prequisites** | **Title/Description** | **Steps** | **Expected Result** | **Pass/Fail** |
|------------------|-----------------|------------------------|-----------|----------------------|---------------|
| TC3-3            |The user has valid login credentials (valid email and password).| Verify login with invalid data - Password. | 1.Open the application.<br>2.Enter a valid Email "koko@roco1.bg" and Password "123456a" of a registered user.<br>Click on "SIGN IN" button. |The system should display an error message indicating that the login attempt failed due to invalid password data.|Pass         |

## TC4:  Mismatch between Username and Password.

| **Test Case ID** | **Prequisites** | **Title/Description** | **Steps** | **Expected Result** | **Pass/Fail** |
|------------------|-----------------|------------------------|-----------|----------------------|---------------|
| TC3-4            |The user has valid login credentials (valid username and password).|Verify mismatch between Username and Password. | 1.Open the application.<br>2.Enter a valid username and password, but ones that do not match.<br>Click on "SIGN IN" button. |The system should display an error message indicating that the login attempt failed due to a mismatch between the entered username and password.|Pass         |

## TC5: Remember Password" Checkbox.

| **Test Case ID** | **Prequisites** | **Title/Description** | **Steps** | **Expected Result** | **Pass/Fail** |
|------------------|-----------------|------------------------|-----------|----------------------|---------------|
| TC3-5            |The user has valid login credentials (valid username and password).|Verify "Remember Password" Checkbox. |1.Open the application.<br>2.Enter a valid username.<br>3.Enter a valid password.<br>4.Check the "Remember Password" checkbox.<br>5.Click on the login button.|The system should remember the user's login credentials for future sessions if the "Remember Password" checkbox is checked. The user should be logged in, and the system should preserve the login state.|Pass         |


