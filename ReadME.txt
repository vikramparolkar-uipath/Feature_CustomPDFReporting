What does this Automation Do?
This is an Attended (or Unattended automation) that allows a tester and/or test developer export Test Execution results from Test Manager as a PDF. The PDF word template can be configured with minimal updates to the Word Template and Studio workflow.

SETUP STEPS
1) Ensure that the 'Test Case Building Block', 'Title Row', 'Screenshots Row', and 'Empty Row' in the "Building Blocks.dotx" is available for your local machine. See Microsoft Documentation for additional setup steps (https://support.microsoft.com/en-us/office/use-quick-parts-and-autotext-in-word-and-outlook-7a527697-058f-4967-b8f1-aae0774e4813#:~:text=Click%20where%20you%20want%20to,Click%20Insert.) 
2) Define Input Argument defaults

CONFIGURATION
> in_ProjectPrefix - provide the Project Prefix in Test Manager
> in_TestSetName - provide the Test Set name in Test Manager
> in_TestExecutionName (optional) - provide the name of a Test Execution. If not provided, the latest Finished test execution will be used
