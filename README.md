# How to Write manual Test Cases
Test cases have a few integral parts that should always be present in fields. However, every test case can be broken down into 7 basic steps.

# Step 1: Test Case ID

Test cases should all bear unique IDs to represent them. In most cases, following a convention for this naming ID helps with organization, clarity, and understanding.

# Step 2: Test Description

This description should detail what unit, feature, or function is being tested or what is being verified.

# Step 3: Test Data

This relates to the variables and their values in the test case. In the example of an email login, it would be the username and password for the account.

# Step 4: Steps to be Executed

These should be easily repeatable steps as executed from the end user’s perspective. For instance, a test case for logging into an email server might include these steps:

Open email server web page.
Enter username.
Enter password.
Click “Enter” or “Login” button.

# Step 5: Expected Result

This indicates the result expected after the test case step execution. Upon entering the right login information, the expected result would be a successful login.

# Step 6: Actual Result and Post-Conditions

As compared to the expected result, we can determine the status of the test case. In the case of the email login, the user would either be successfully logged in or not. The post-condition is what happens as a result of the step execution such as being redirected to the email inbox.

# Step 7: Pass/Fail

Determining the pass/fail status depends on how the expected result and the actual result compare to each other.

Same result = Pass
Different results = Fail
