 **Classroom Assignment <5>: Automating Frame and Alert Interactions with Text Verification**

Learning Objective:
Learn to automate interactions with frames, alerts, and verify text based on actions using Selenium WebDriver.
Expected Time:
Best Case: 15 minutes
Average Case: 20 minutes


/*Details:
Automate interactions with frames, trigger alerts, and verify the displayed text based on actions using Selenium 
WebDriver on the given application.


Precondition:
- Initialize ChromeDriver
- Load the URL (https://www.w3schools.com/js/tryit.asp?filename=tryjs_prompt)
- Maximize the browser window
- Switch to the frame
- Add an implicit wait to ensure the webpage elements are fully loaded


Requirements:
- Click the "Try It" button inside the frame
- Click OK/Cancel in the alert that appears
- Confirm the action is performed correctly by verifying the text displayed

- 
Hints to Solve:
- Use Selenium methods such as `switchTo().frame()`, `findElement()`, `click()`, `switchTo().alert()`, `sendKeys()`, and 
`alert.accept()` or `alert.dismiss()` to perform the required actions.
- Use Conditional statements to verify the text based on the action performed.
 * 
 * Expected Outcome:
Upon completion, you should be able to:
- Automate interactions with frames, trigger alerts, perform actions.
- Verify the text based on the actions taken using Selenium WebDriver methods
