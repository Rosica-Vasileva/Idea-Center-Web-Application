
## 4. Test Case 4 (Profile Management)
Upon successful Sign In, logged users should be able to navigate to My Profile page, edit their Profile details, and
view their Ideas count. This involves the changing of profile picture inserted via URL, and editing of user data fields
including First Name, Last Name, City, and Describe Yourself.

## TC1:Login with Registered Profile.
.
| **Test Case ID** | **Prequisites** | **Title/Description** | **Steps** | **Expected Result** | **Pass/Fail** |
|------------------|-----------------|------------------------|-----------|----------------------|---------------|
| TC4-1            |Registered user|Verify Successful Login with Registered Profile. |1.Open the application.<br>2.Enter a valid username.<br>3.Enter a valid password.<br>4.Click on the signin button. |The system should authenticate the user, and upon successful login, the user should be redirected to the home page or the designated user dashboard.|Pass         |


## TC2: Navigate to "My Profile" Page.
.
| **Test Case ID** | **Prequisites** | **Title/Description** | **Steps** | **Expected Result** | **Pass/Fail** |
|------------------|-----------------|------------------------|-----------|----------------------|---------------|
| TC4-2            |Registered user|Navigate to My Profile Page. | 1.Locate and click on the "My profile" link or button.<br>2.Observe the page that opens. |The user is successfully redirected to their My Profile pgae.|Pass         |


## TC3:Verify the ability to change Profile picture via URL.
.

| **Test Case ID** | **Prequisites** | **Title/Description** | **Steps** | **Expected Result** | **Pass/Fail** |
|------------------|-----------------|------------------------|-----------|----------------------|---------------|
| TC4-3            |The user is logged in and is on the My Profile page.|Verify the ability to change Profile picture via URL. |1.Open the application.<br>2.Sign in with valid credentials.<br>3.Navigate to the My Profile page.<br>4.Click on the "Change Profile Picture" option.<br>5.Insert a valid image URL.<br>5.Save the changes.|The system should allow the user to change the profile picture by providing a valid image URL and successfully save the changes.|Pass       |


## TC4: Edit Profile Details.
.

| **Test Case ID** | **Prequisites** | **Title/Description** | **Steps** | **Expected Result** | **Pass/Fail** |
|------------------|-----------------|------------------------|-----------|----------------------|---------------|
| TC4-4            |The user is logged in and is on the My Profile page.|To ensure that a logged user can edit their profile details including First Name,Last Name,City and Describe Yourself. | 1.Locate and click on the "Edit profile" similar option.<br>2.Edit the First Name "Rosica" ,Last Name "Vasileva" ,City "Sofia" and Disctibe Yourself fields "Hello, I'm Rositsa and I'm a QA engineering student at Softuni."<br>3.Enter a valid image URL<br>4.Save the changes.|The system should allow the user to successfully edit and save changes to the profile details.|Pass         |

