## Use Case 2 (User Registration)
Unregistered users should be able to successfully go through the Sign Up process. This involves the utilization of
fields such as Username, Email, and Password, all subject to their respective constraints and character type
acceptance. User should have the option to Sign Up via Facebook or Google if he prefers.
The Sign Up page is accessed from the Home page. It contains form fields for entering a Username, Email,
Password, and Repeat password. The form also includes a checkbox for agreeing to Terms of service, a hyperlink
to view the full Terms of service document and a Register button to submit the form. The acceptable requirements
for each field are specified as follows:
Username: A 2-30 character field, accepting all character types.
Email: Requires a valid email, 6-254 characters long.
Password: Any characters are acceptable, with a length of 6-30 characters.
Repeat Password: Must match password.
There is an alternative sign up options via Google or Facebook.

## Unregistered Users

## TC1: Verify SIGN UP labels and button.

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
| TC2-5           |The system supports usernames with lengths within the boundary, i.e., at both the minimum and maximum allowed lengths.|  Verify registration with Username on the upper boundary. | 1.Open the application.<br>2.Click on SIGN UP FOR FREE button.<br>3.Enter for username 30 symbols.<br>4.Enter email "test@test.bg".<br>5.Enter password and repeat password "123456".<br>6.Click on SIGN UP button. |User is successfull registered.|Pass        |

## TC6: Verify registration with Username above the upper boundary .

| **Test Case ID** | **Prequisites** | **Title/Description** | **Steps** | **Expected Result** | **Pass/Fail** |
|------------------|-----------------|------------------------|-----------|----------------------|---------------|
| TC2-6          |Users is not logged in|  Verify registration with Username above the upper boundary. | 1.Open the application.<br>2.Click on SIGN UP FOR FREE button.<br>3.Enter for username 31 symbols.<br>4.Enter email "test@test.bg".<br>5.Enter password and repeat password "123456".<br>6.Click on SIGN UP button. |The field allows only 30 characters.|Pass        |

## TC7: Verify SIGN UP page.

| **Test Case ID** | **Prequisites** | **Title/Description** | **Steps** | **Expected Result** | **Pass/Fail** |
|------------------|-----------------|------------------------|-----------|----------------------|---------------|
| TC2-7           |Users is not logged in|  Verify SIGN UP page. | 1.Open the application.<br>2.Click on SIGN UP FOR FREE button. |Loading the application registration form.|Pass        |

## TC8:Registration with invalid email format. .

| **Test Case ID** | **Prequisites** | **Title/Description** | **Steps** | **Expected Result** | **Pass/Fail** |
|------------------|-----------------|------------------------|-----------|----------------------|---------------|
| TC2-8           |Users is not logged in|  Verify registration with Username on the lower boundary. | 1.Open the application.<br>2.Click on SIGN UP FOR FREE button.<br>3.Enter for username "roco123".<br>4.Enter email "qugd".<br>5.Enter password and repeat password "123456".<br>6.Click on SIGN UP button. |A message appears that the email address format is entered incorrectly.|Fall  

## TC9: Verify registration with Email on the lower boundary .

| **Test Case ID** | **Prequisites** | **Title/Description** | **Steps** | **Expected Result** | **Pass/Fail** |
|------------------|-----------------|------------------------|-----------|----------------------|---------------|
| TC2-9            |Users is not logged in|  Verify registration with email on the lower boundary. | 1.Open the application.<br>2.Click on SIGN UP FOR FREE button.<br>3.Enter for username "roco123".<br>4.Enter email "b@.b".<br>5.Enter password and repeat password "123456".<br>6.Click on SIGN UP button. |Validation message for email should appears- email has to be at least 6 characters.|Pass        |

## TC10: Verify registration with Email in boundary .

| **Test Case ID** | **Prequisites** | **Title/Description** | **Steps** | **Expected Result** | **Pass/Fail** |
|------------------|-----------------|------------------------|-----------|----------------------|---------------|
| TC2-10            |Users is not logged in|  Verify registration with Username on the lower boundary. | 1.Open the application.<br>2.Click on SIGN UP FOR FREE button.<br>3.Enter for username "roco123".<br>4.Enter email "f@a.bg".<br>5.Enter password and repeat password "123456".<br>6.Click on SIGN UP button. |User is successfully registration.|Pass        |

## TC11: Verify registration with Email in boundary .

| **Test Case ID** | **Prequisites** | **Title/Description** | **Steps** | **Expected Result** | **Pass/Fail** |
|------------------|-----------------|------------------------|-----------|----------------------|---------------|
| TC2-11           |Users is not logged in|  Verify registration with Username on the lower boundary. | 1.Open the application.<br>2.Click on SIGN UP FOR FREE button.<br>3.Enter for username "roco123".<br>4.Enter email "254 symbols".<br>5.Enter password and repeat password "123456".<br>6.Click on SIGN UP button. |Validation message for Email should appears.|Fall        |

## TC12: Verify registration with Email on the upper boundary .

| **Test Case ID** | **Prequisites** | **Title/Description** | **Steps** | **Expected Result** | **Pass/Fail** |
|------------------|-----------------|------------------------|-----------|----------------------|---------------|
| TC2-12           |Users is not logged in|  Verify registration with Username on the lower boundary. | 1.Open the application.<br>2.Click on SIGN UP FOR FREE button.<br>3.Enter for username "roco123".<br>4.Enter email "255 symbols".<br>5.Enter password and repeat password "123456".<br>6.Click on SIGN UP button. |Validation message for Email should appears.|Fall        |

## TC13: Verify SIGN UP labels and button.

| **Test Case ID** | **Prequisites** | **Title/Description** | **Steps** | **Expected Result** | **Pass/Fail** |
|------------------|-----------------|------------------------|-----------|----------------------|---------------|
| TC2-13            |Users is not logged in| Verify SIGN UP labels and button. | 1.Open the application.<br>2.Click on SIGN UP FOR FREE button. |The following labels are present:<br>-Your Username<br>-Your Email address<br>-Password <br>-Repeat password <br>-I agree all statements and Terms and Services<br>-Register button<br>-"SIGN WITH GOOGLE"<br>-"SIGN WITH FACEBOOK" | Fail          |

## TC14: Verify registration with Password and Repeat password on the lower boundary .

| **Test Case ID** | **Prequisites** | **Title/Description** | **Steps** | **Expected Result** | **Pass/Fail** |
|------------------|-----------------|------------------------|-----------|----------------------|---------------|
| TC2-14           |Users is not logged in|  Verify registration with  Password and Repeat password on the lower boundary. | 1.Open the application.<br>2.Click on SIGN UP FOR FREE button.<br>3.Enter for username "roco123".<br>4.Enter email "test@test.bg".<br>5.Enter password and repeat password "12345" or "123Ab".<br>6.Click on SIGN UP button. |Password has to be at least 6 symbols.|Pass       |

## TC15: Verify registration with Password and Repeat password on the upper boundary .

| **Test Case ID** | **Prequisites** | **Title/Description** | **Steps** | **Expected Result** | **Pass/Fail** |
|------------------|-----------------|------------------------|-----------|----------------------|---------------|
| TC2-15           |Users is not logged in|  Verify registration with  Password and Repeat password on the lower boundary. | 1.Open the application.<br>2.Click on SIGN UP FOR FREE button.<br>3.Enter for username "roco1235".<br>4.Enter email "test@test.bg".<br>5.Enter password and repeat password "31 symbols"or "31 characters".<br>6.Click on SIGN UP button. |Password has to be at max 30 symbols.|Fall       |

## TC16: Verify registration with Password and Repeat password in the  boundary .

| **Test Case ID** | **Prequisites** | **Title/Description** | **Steps** | **Expected Result** | **Pass/Fail** |
|------------------|-----------------|------------------------|-----------|----------------------|---------------|
| TC2-16           |Users is not logged in|  Verify registration with  Password and Repeat password in the  boundary. | 1.Open the application.<br>2.Click on SIGN UP FOR FREE button.<br>3.Enter for username "roco1235".<br>4.Enter email "test@test.bg".<br>5.Enter password and repeat password "123456" оr "test11" .<br>6.Click on SIGN UP button. |User is successfully registration.|Pass       |

## TC17: Verify registration with Password and Repeat password in the boundary .

| **Test Case ID** | **Prequisites** | **Title/Description** | **Steps** | **Expected Result** | **Pass/Fail** |
|------------------|-----------------|------------------------|-----------|----------------------|---------------|
| TC2-17           |Users is not logged in|  Verify registration with  Password and Repeat password in the  boundary. | 1.Open the application.<br>2.Click on SIGN UP FOR FREE button.<br>3.Enter for username "roco1235".<br>4.Enter email "test@test.bg".<br>5.Enter password and repeat password "30 symbols" or  "30 characters".<br>6.Click on SIGN UP button. |User is successfully registration..|Pass       |


