## Test Case 6 (Idea Management)
On the My Ideas page, logged users should see all their ideas listed. Each idea should have options for VIEW, EDIT,
and DELETE. If no ideas have been created yet, a No ideas yet! message should be displayed. Users also should have
the option to search for ideas, based on keywords.

## TC1:Viewing My Ideas by Logged-In Users.


| **Test Case ID** | **Prequisites** | **Title/Description** | **Steps** | **Expected Result** | **Pass/Fail** |
|------------------|-----------------|------------------------|-----------|----------------------|---------------|
| TC6-1           |The user is registered in the system.<br>The user is logged into their account.|Logged-in users should be able to successfully view a list of all their ideas on the "My Ideas" page. |1. Navigate to the "My Ideas" page.<br>2. Verify that all ideas created by the user are listed. |The "My Ideas" page should successfully display a list of all ideas created by the logged-in user.|Pass         |


## TC2:View, Edit, and Delete Ideas on "My Ideas" Page.


| **Test Case ID** | **Prequisites** | **Title/Description** | **Steps** | **Expected Result** | **Pass/Fail** |
|------------------|-----------------|------------------------|-----------|----------------------|---------------|
| TC6-2           |The user is registered in the system.<br>The user is logged into their account.|Logged-in users should be able to view a list of all their ideas on the "My Ideas" page. Each idea entry should provide options for VIEW, EDIT, and DELETE. |1.Navigate to the "My Ideas" page.<br>2.Verify that all created ideas are listed.<br>3.For each idea entry, check for VIEW, EDIT, and DELETE options. |The "My Ideas" page should display a list of all ideas created by the logged-in user.Each idea entry should include options for VIEW, EDIT, and DELETE.|Pass         |


## TC3:Display "No Ideas Yet!" Message.


| **Test Case ID** | **Prequisites** | **Title/Description** | **Steps** | **Expected Result** | **Pass/Fail** |
|------------------|-----------------|------------------------|-----------|----------------------|---------------|
| TC6-3            |The user is registered in the system.<br>The user is logged into their account.|If the logged-in user has not created any ideas, a "No ideas yet!" message should be displayed on the "My Ideas" page. |1. Navigate to the "My Ideas" page.|The "My Ideas" page should display a message stating "No ideas yet!" since the user has not created any ideas.|Pass         |
