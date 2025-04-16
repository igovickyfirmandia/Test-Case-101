# Test Case 101

## What is Test Case?
Well, test case is set of conditions or a variable under which a tester will determine whether an application, software system, or one of its feature is working or not.

## Crucial Component of Test Case
| **Component**            | **Description**                                             |
|--------------------------|-------------------------------------------------------------|
| Test Case ID             | Unique identifier (e.g TC_001)                              |
| Module Name              | Module/Feature being tested (e.g Search functionality)      |
| Title                    | Shor description about what's being tested                  |
| Pre-Conditions           | Reuired state before running the test                       |
| Test Steps               | Sequential steps to perform the test                        |
| Test Data                | Data/Inputs needed to execute the test                      |
| Expected Result          | What result are we expected when the system works correctly |
| Actual Result            | The result of the testi                                     |
| Status                   | Pass/Fail/Blocked/Skipped                                   |
| Priority/Severity Level  | Bug Priority & Severity Level                               |
| Created By               | The author information                                      |
| Date                     | Information about when the test created/executed            |
| Remarks/Note             | Additional information (comment/screenshot/references)      |
| Test Type (optional)     | Manual or Automated                                         |

Of course we can add some information that might be needed in the test case. For example:
  * Role (User/Admin/etc)
  * Test Platform (Android/iOS/Windows/macOS)
  * Test Environment (Staging/Test Production/etc)

Also, test case execution Summary information would be nice if can be added ate the end of the report.
  * Total Test Case
  * Executed Test Case
  * Number of Test Case status
    * Pass
    * Failed
    * Blocked
    * Skipped

These additional information can be adjusted according to what we need

## Types of Test Cases
Test case can be categorized based on what the test is conducted
| **Type of Test Cases** | **Description**                                                             |
|------------------------|-----------------------------------------------------------------------------|
| Functional             | Specific to test the functionality of the system (e.g Search functionality) |
| Non-Functional         | Focused on non-functional (e.g usability, performance, etc)                 |
| UI Test Case           | Validating the UI, responsivesness, design elements                         |
| Positive Test Case     | Use valid data/inputs to ensure the system works as expected                |
| Negative Test Case     | Use invalid data/inputs to check the error handling from the system         |
| Boundary Test Case     | Check max/min limit of an input (e.g Max Character)                         |
| Integration Test Case  | Validate the data flow                                                      |
| Sanity Test Case       | Test to spesific functionality after a change                               |
| Smoke Test Case        | Basic checks to verify the system can work properly after a build           |
| Regression Test Case   | Re-test existing feature after bug fix/change                               |

## Format for Report Test Case
We can report test case execution result using table in Excel format or Test Management Tools like TestRail,Xray, etc.
This table below is an example:
| **ID** | **Module**     | **Test Case Title** | **Pre-Conditions** | **Test Steps** | **Test Data**      | **Expected Result**     | **Actual Result**           | **Status** | **Priority** | **Remarks**             |
|--------|----------------|---------------------|--------------------|----------------|--------------------|-------------------------|-----------------------------|------------|--------------|-------------------------|
| TC_01  | Authentication | User Valid Login    | User on Login Page | *Step 1-5      | Valid Credential   | User successfully login | User can login successfully | Pass       | High         | -                       |
| TC_02  | Authentication | User Invalid Login  | User on Login Page | *Step 1-4      | Invalid Credential | User can't login        | User can't login            | Failed     | High         | *your note/evidence/etc |

And this is an example of Report Test Case: [Report]()

## Test Case Example
Here is an example of Test Case I've created: [Test Case Example]()










