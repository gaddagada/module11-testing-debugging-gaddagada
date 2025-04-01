# Developer Kickstart: Testing and Debugging
This repository is an essential segment of the Developer Kickstart curriculum at Cloud Code Academy. Tailored specifically for up-and-coming Salesforce developers, this module plunges into the crucial aspects of testing and debugging, underscoring the necessity of robust test classes, effective debugging strategies, and the maintenance of high code coverage.

## Goals of the Practice
During this repository, you will deepen your grasp of:

- The imperative role of test classes in ensuring the reliability and stability of your Apex code within Salesforce.
- Crafting and deploying well-structured test methods to cover a multitude of scenarios, both positive and negative.
- The importance of achieving and maintaining a high code coverage percentage, ensuring every line of code is vetted for functionality.
- Mastering Salesforce's built-in debugging tools, such as the Developer Console, to identify, diagnose, and resolve issues efficiently.
- Incorporating systematic logging and exception handling to provide clarity on runtime behaviors and unexpected errors.

By excelling in these testing and debugging techniques, you'll bolster your capability to write resilient and fault-tolerant code. This strengthens your expertise in ensuring that Salesforce applications are not only functional but also reliable, emphasizing the best practices that underpin top-tier Salesforce development.

## Setup
[Setup Overview](https://learn.cloudcodeacademy.com/courses/salesforce-developer-kickstart-program/lectures/47317682)

## Setup Checklist
1. Create/Configure a trailhead playground or developer org to do your work throughout this program.
2. Install Visual Studio Code from [here](https://code.visualstudio.com/download).
3. Install Salesforce Extension Pack in Visual Studio Code. This can be done by searching 'Salesforce Extension Pack' in the Extensions view in VS Code and clicking Install.
4. Authorize your org in Visual Studio Code. Press `Ctrl/Cmd + Shift + P` to open the command palette and type 'SFDX: Authorize an Org', then press Enter. Follow the steps in the browser to log in to your org, then return to VS Code.
5. Save and deploy your changes into Salesforce from your local machine. This can be done through the command pallet or right-clicking the file you want to deploy and using the option `SFDX: Deploy this source to org`

## Getting Started
1. Navigate to the folder force-app/main/default/ and deploy the metadata to your Salesforce org. Right-click on the folder and select `SFDX: Deploy Source to Org`.
2. Review the files provided including the test class to understand the challenges.
3. Update the code and deploy it to your Salesforce org.
4. Run the test class to validate your code. Use `Ctrl/Cmd + Shift + P` to open the command palette and type 'SFDX: Run Apex Tests', then press Enter. You can also use `Run All Test` or `Run Test` on the test class.
5. Push your changes to your GitHub repository and submit the link to the assignment in the submission form in Slack.

## Resources

If you get stuck at any point, here are some resources that might help:

- [Apex Developer Guide](https://developer.salesforce.com/docs/atlas.en-us.apexcode.meta/apexcode/apex_dev_guide.htm)
- [Salesforce Stack Exchange](https://salesforce.stackexchange.com/)
- [Visual Studio Code Documentation](https://code.visualstudio.com/docs)
- [Salesforce Extensions for Visual Studio Code](https://developer.salesforce.com/tools/vscode/)

And remember, programming is often about solving problems, so don't be afraid to use search engines to find answers to your questions.

Good luck with your learning journey in Salesforce development!
