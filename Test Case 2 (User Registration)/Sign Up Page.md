## Test Case 2 (User Registration)
Unregistered users should be able to successfully go through the Sign Up process. This involves the utilization of
fields such as Username, Email, and Password, all subject to their respective constraints and character type
acceptance. User should have the option to Sign Up via Facebook or Google if he prefers.


The Sign Up page is accessed from the Home page. It contains form fields for entering a Username, Email,
Password, and Repeat password. The form also includes a checkbox for agreeing to Terms of service, a hyperlink
to view the full Terms of service document and a Register button to submit the form. The acceptable requirements
for each field are specified as follows:

# Username: A 2-30 character field, accepting all character types.

# Email: Requires a valid email, 6-254 characters long.

# Password: Any characters are acceptable, with a length of 6-30 characters.

# Repeat Password: Must match password.

# There is an alternative sign up options via Google or Facebook.


# Unregistered Users

# TC1: Verify SIGN UP labels and button.

| **Test Case ID** | **Prequisites** | **Title/Description** | **Steps** | **Expected Result** | **Pass/Fail** |
|------------------|-----------------|------------------------|-----------|----------------------|---------------|
| TC2-1            |Users is not logged in| Verify SIGN UP labels and button. | 1.Open the application.<br>2.Click on SIGN UP FOR FREE button. |The following labels are present:<br>-Your Username<br>-Your Email address<br>-Password <br>-Repeat password <br>-I agree all statements and Terms and Services<br>-Register button<br>-"SIGN WITH GOOGLE"<br>-"SIGN WITH FACEBOOK" | Fail          |

## TC2: Verify the field length.

| **Test Case ID** | **Prequisites** | **Title/Description** | **Steps** | **Expected Result** | **Pass/Fail** |
|------------------|-----------------|------------------------|-----------|----------------------|---------------|
| TC2-2           |Users is not logged in| Verify the field length. | 1.Open the application.<br>2.Click on SIGN UP FOR FREE button.<br>Try to enter:<br> - more than 30 symbols in Username field;<br> - more than 254 in Email field;<br> - more than 30 characters in Password field;<br> - more than 30 characters in Repeat Password field; |User should not be able to enter more symbols than the specified one.| Pass<br> Comment:  The Username field only allows 30 characters to be entered.       |

## TC3: Verify registration with Username on the lower boundary .

| **Test Case ID** | **Prequisites** | **Title/Description** | **Steps** | **Expected Result** | **Pass/Fail** |
|------------------|-----------------|------------------------|-----------|----------------------|---------------|
| TC2-3            |The system supports usernames with a minimum allowed length.|Verify that the registration process successfully accepts and processes a user registration with a username at the lower boundary of the allowed length.| 1.Open the application.<br>2.Click on SIGN UP FOR FREE button.<br>3.Enter for username "B".<br>4.Enter email "test@test.bg".<br>5.Enter password and repeat password "123456".<br>6.Click on SIGN UP button. |Validation message for Username should appears.|Pass        |

## TC4: Verify registration with Username on the upper boundary .

| **Test Case ID** | **Prequisites** | **Title/Description** | **Steps** | **Expected Result** | **Pass/Fail** |
|------------------|-----------------|------------------------|-----------|----------------------|---------------|
| TC2-4           |Users is not logged in|  Verify registration with Username on the upper boundary. | 1.Open the application.<br>2.Click on SIGN UP FOR FREE button.<br>3.Enter for username "BB".<br>4.Enter email "test@test.bg".<br>5.Enter password and repeat password "123456".<br>6.Click on SIGN UP button. |User is successfull registered.|Pass        |

## TC5: Verify registration with Username in border .

| **Test Case ID** | **Prequisites** | **Title/Description** | **Steps** | **Expected Result** | **Pass/Fail** |
|------------------|-----------------|------------------------|-----------|----------------------|---------------|
| TC2-5           |The system supports usernames with lengths within the boundary, i.e., at both the minimum and maximum allowed lengths.| Verify that the registration process successfully accepts and processes a user registration with a username at the boundary of the allowed length. | 1.Open the application.<br>2.Click on SIGN UP FOR FREE button.<br>3.Enter for username 30 symbols.<br>4.Enter email "test@test.bg".<br>5.Enter password and repeat password "123456".<br>6.Click on SIGN UP button. |User is successfull registered.|Pass        |

## TC6: Verify registration with Username above the upper boundary .

| **Test Case ID** | **Prequisites** | **Title/Description** | **Steps** | **Expected Result** | **Pass/Fail** |
|------------------|-----------------|------------------------|-----------|----------------------|---------------|
| TC2-6          |The system supports usernames with lengths at the upper boundary of the allowed range.| Verify that the registration process appropriately handles and communicates an attempt to register with a username exceeding the maximum allowed length. | 1.Open the application.<br>2.Click on SIGN UP FOR FREE button.<br>3.Enter for username 31 symbols.<br>4.Enter email "test@test.bg".<br>5.Enter password and repeat password "123456".<br>6.Click on SIGN UP button. |The field allows only 30 characters.|Pass        |

## TC7: Verify SIGN UP page.

| **Test Case ID** | **Prequisites** | **Title/Description** | **Steps** | **Expected Result** | **Pass/Fail** |
|------------------|-----------------|------------------------|-----------|----------------------|---------------|
| TC2-7           |The user is on the SIGN UP page.| Verify that the SIGN UP page is displayed and functions correctly. This includes checking the layout, content, and functionality of the SIGN UP page to ensure a seamless and user-friendly experience. | 1.Open the application.<br>2.Click on SIGN UP FOR FREE button. |Loading the application registration form.|Pass        |

## TC8:Registration with invalid email format.

| **Test Case ID** | **Prequisites** | **Title/Description** | **Steps** | **Expected Result** | **Pass/Fail** |
|------------------|-----------------|------------------------|-----------|----------------------|---------------|
| TC2-8           |The registration page allows input of an email address.|  Verify that the registration process appropriately handles and communicates an attempt to register with an invalid email format.| 1.Open the application.<br>2.Click on SIGN UP FOR FREE button.<br>3.Enter for username "roco123".<br>4.Enter email "qugd".<br>5.Enter password and repeat password "123456".<br>6.Click on SIGN UP button. |A message appears that the email address format is entered incorrectly.|Fall  

## TC9: Registration with Email Address Below Minimum Length - 4  characters .

| **Test Case ID** | **Prequisites** | **Title/Description** | **Steps** | **Expected Result** | **Pass/Fail** |
|------------------|-----------------|------------------------|-----------|----------------------|---------------|
| TC2-9            |The system supports email addresses with a minimum allowed length of 6 characters.| Verify that the system displays an error message when attempting to register with an email address containing fewer than 6 characters.| 1.Open the application.<br>2.Click on SIGN UP FOR FREE button.<br>3.Enter for username "roco123".<br>4.Enter email "b@.b".<br>5.Enter password and repeat password "123456".<br>6.Click on SIGN UP button. |The system should display an error message indicating that a valid email address requires a minimum of 6 characters.|Pass        |

## TC10: Registration with Email Address at Minimum Length - 6  characters .

| **Test Case ID** | **Prequisites** | **Title/Description** | **Steps** | **Expected Result** | **Pass/Fail** |
|------------------|-----------------|------------------------|-----------|----------------------|---------------|
| TC2-10            |The system supports email addresses with a minimum allowed length of 6 characters.| Verify that the registration process successfully accepts and processes a user registration with a valid email address containing exactly 6 characters. | 1.Open the application.<br>2.Click on SIGN UP FOR FREE button.<br>3.Enter for username "roco123".<br>4.Enter email "f@a.bg".<br>5.Enter password and repeat password "123456".<br>6.Click on SIGN UP button. | The system should successfully process the registration with a valid email address containing 6 characters.|Pass        |

## TC11:Registration with Email Address at Maximum Length - 254  characters .

| **Test Case ID** | **Prequisites** | **Title/Description** | **Steps** | **Expected Result** | **Pass/Fail** |
|------------------|-----------------|------------------------|-----------|----------------------|---------------|
| TC2-11           |The system supports email addresses with a maximum allowed length of 254 characters.| Verify that the registration process successfully accepts and processes a user registration with an email address at the upper boundary of the allowed length (254 characters).| 1.Open the application.<br>2.Click on SIGN UP FOR FREE button.<br>3.Enter for username "roco123".<br>4.Enter email "254  characters".<br>5.Enter password and repeat password "123456".<br>6.Click on SIGN UP button. |Validation message for Email should appears.|Fall        |

## TC12: Registration with Email Address Above Maximum Length - 255  characters.

| **Test Case ID** | **Prequisites** | **Title/Description** | **Steps** | **Expected Result** | **Pass/Fail** |
|------------------|-----------------|------------------------|-----------|----------------------|---------------|
| TC2-12           |The system supports email addresses with a maximum allowed length of 254 characters.| Verify that the system displays an error message when attempting to register with an email address containing more than 254 characters. | 1.Open the application.<br>2.Click on SIGN UP FOR FREE button.<br>3.Enter for username "roco123".<br>4.Enter email "255  characters".<br>5.Enter password and repeat password "123456".<br>6.Click on SIGN UP button. |The system should display an error message indicating that a valid email address requires a maximum of 254 characters.|Fall        |


## TC13:Registration with Password and Repeat Password Below Minimum Length - 5  characters.

| **Test Case ID** | **Prequisites** | **Title/Description** | **Steps** | **Expected Result** | **Pass/Fail** |
|------------------|-----------------|------------------------|-----------|----------------------|---------------|
| TC2-13           |The system supports passwords with a minimum allowed length of 6 characters and a maximum allowed length of 30 characters.| Verify that the system displays an error message when attempting to register with a password containing fewer than 6 characters.| 1.Open the application.<br>2.Click on SIGN UP FOR FREE button.<br>3.Enter for username "roco123".<br>4.Enter email "test@test.bg".<br>5.Enter password and repeat password "12345" or "123Ab".<br>6.Click on SIGN UP button. |The system should display an error message indicating that a valid password requires a minimum of 6 characters.|Pass       |

## TC14:Registration with Password and Repeat Password Above Maximum Length - 31  characters .

| **Test Case ID** | **Prequisites** | **Title/Description** | **Steps** | **Expected Result** | **Pass/Fail** |
|------------------|-----------------|------------------------|-----------|----------------------|---------------|
| TC2-14          |The system supports passwords with a minimum allowed length of 6 characters and a maximum allowed length of 30 characters.|Verify that the system displays an error message when attempting to register with a password containing more than 30 characters. | 1.Open the application.<br>2.Click on SIGN UP FOR FREE button.<br>3.Enter for username "roco1235".<br>4.Enter email "test@test.bg".<br>5.Enter password and repeat password  "31 characters".<br>6.Click on SIGN UP button. |The system should display an error message indicating that a valid password requires a maximum of 30 characters.|Fall       |

## TC15:Registration with Password and Repeat Password at Minimum Length - 6 characters .

| **Test Case ID** | **Prequisites** | **Title/Description** | **Steps** | **Expected Result** | **Pass/Fail** |
|------------------|-----------------|------------------------|-----------|----------------------|---------------|
| TC2-16           |The system supports passwords with a minimum allowed length of 6 characters and a maximum allowed length of 30 characters.|  Verify registration with  Password and Repeat password in the  boundary. | 1.Open the application.<br>2.Click on SIGN UP FOR FREE button.<br>3.Enter for username "roco1235".<br>4.Enter email "test@test.bg".<br>5.Enter password and repeat password "123456" оr "test11" .<br>6.Click on SIGN UP button. |User is successfully registration.|Pass       |

## TC16: Registration with Password and Repeat Password at Maximum Length - 30  characters.

| **Test Case ID** | **Prequisites** | **Title/Description** | **Steps** | **Expected Result** | **Pass/Fail** |
|------------------|-----------------|------------------------|-----------|----------------------|---------------|
| TC2-17           |The system supports passwords with a minimum allowed length of 6 characters and a maximum allowed length of 30 characters.| Verify that the registration process successfully accepts and processes a user registration with a valid password containing exactly 30 characters. | 1.Open the application.<br>2.Click on SIGN UP FOR FREE button.<br>3.Enter for username "roco1235".<br>4.Enter email "test@test.bg".<br>5.Enter password and repeat password "30  characters" .<br>6.Click on SIGN UP button. |User is successfully registration.|Pass       |


