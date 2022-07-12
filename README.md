# Practical Assignment

Your mission, if you choose to accept, is to build the *running application equivalent of your resume*. This message will self-destruct in 3… 2… 1…

![self-destruct-mission-impossible](https://user-images.githubusercontent.com/3520532/167459946-9441a9c6-bcc4-4243-893d-334097d2d1ca.gif)

### Instructions

1. Fork this repository into your GitHub account and close your fork locally (the fork button is at the top right)
    - If you do not have a GitHub account or aren't familiar with git, you can download this repo instead: expand the green "Code" button, then select "Download ZIP"
2. Complete your assignment (see Assignment Guidelines section below)
3. Submit the assignment
    - Option 1. Commit the code to your fork's main branch and email us a link to your repo
    - Option 2. ZIP up the project(s) and email it to Kat (please delete the **bin** and **obj** folders before zipping)

> If your project needs special instructions for setup and/or use, include those directions in your repo by adding a new file `instructions.md` and explain in there.

#### Project Structure

Depending on how many parts your submission has, you might be wondering how to organize it. Here's some general guidance:

- If your submission only has one `.sln` file (regardless of how many projects), then you can put the entire thing directly in the `/src` folder.
  - Example: See my https://github.com/LanceMcCarthy/CommonHelpers repo's `/src` folder.
- If your submission has multiple technologies that don't work well inside the same folder, then use a sub-folder for each separate thing.
  - Example: See my https://github.com/LanceMcCarthy/DevOpsExamples repo's `/src` folder.


## Assignment Guidelines

Here are the general guidelines for the assignment:

* You have carte blanche over the project’s vision and direction; this is intended for you to be able to use the platform features to show of your skills.
* Choose your preferred option to build the application
    * Use **Telerik UI for Blazor** (best option, uses ASP.NET Core and .NET 5/.NET 6)
    * Use **Telerik UI for ASP.NET AJAX** (aka 'webforms', uses .NET Framework)
* Implement **Telerik Reporting** and the HTML5 ReportViewer in some fashion. This will demonstrate:
    * Your ability to use a SQL data source to render information in the Report
    * Use a pre-existing REST API, the Reporting REST API is just added to a project, it handles requests for you (details in documentation links below).
* Bonus points for being creative, thinking outside the box with product features

## Resources

Here are the resources you’ll need to help implement the assignment.

### Documentation

* [Telerik UI for Blazor docs](https://docs.telerik.com/blazor-ui/introduction)
    * [Getting started](https://docs.telerik.com/devtools/aspnet-ajax/getting-started/first-steps-msi) (server-side Blazor)
* [Telerik UI for ASP.NET AJAX docs](https://docs.telerik.com/devtools/aspnet-ajax/introduction)
    * [Getting Started](https://docs.telerik.com/devtools/aspnet-ajax/getting-started/first-steps-msi) (using MSI installer)
* [Telerik Reporting docs](https://docs.telerik.com/reporting/overview)
    * [Video Onboarding](https://docs.telerik.com/reporting/embedding-reports/display-reports-in-applications/web-application/blazor-report-viewer/overview) course - This is only 2 hours and shows you a lot of good getting started information.
    * [Desiging Reports Guide](https://docs.telerik.com/reporting/getting-started/first-steps-designing) - This quick tutorial is to show you some basic info on creating a Report.
    * [Displaying Reports Guide](https://docs.telerik.com/reporting/getting-started/first-steps-integrating) - This quick tutorial is to create a quick throw-away webapp project to familiarize you with how a Report Viewer is used.
    * [How to display Reports in an application](https://docs.telerik.com/reporting/using-reports-in-applications/overview) - These docs are for the real deal. After yo've designed your report, now it's time to add a Report Viewer to your app-of-choice and display it at runtime.
        * [In a Blazor project](https://docs.telerik.com/reporting/using-reports-in-applications/display-reports-in-applications/web-application/blazor-report-viewer/overview)
        * [In an AJAX project](https://docs.telerik.com/reporting/using-reports-in-applications/display-reports-in-applications/web-application/html5-asp.net-web-forms-report-viewer/overview)

> Important Note: you can get a product license for any of the items above by clicking "DOWNLOAD FREE TRIAL" button on any product's Overview page. This will automatically assign a new trial license to your Telerik account; [go here for Telerik Reporting](https://www.telerik.com/products/reporting.aspx), [go here for UI for Blazor](https://www.telerik.com/blazor-ui) and/or [go here for UI for ASP.NET AJAX](https://www.telerik.com/products/aspnet-ajax.aspx).

### Demos

Below are links to the relevant live demos. You’ll find a rich set if implementations as well as the source code used to create that example:

* [UI for Blazor live demos](https://demos.telerik.com/blazor-ui/)
* [UI for ASP.NET AJAX live demos](https://demos.telerik.com/aspnet-ajax/)
* [Telerik Reporting live demos](https://demos.telerik.com/reporting)


### Forums

Telerik forums contains a rich history of conversations between the Technical Support Engineers and other community members. You can find commonly asked questions, but also many edge cases.

* [UI for Blazor forums](https://www.telerik.com/forums/blazor)
* [UI for ASP.NET AJAX forums](https://www.telerik.com/forums/aspnet-ajax)
* [Telerik Reporting forums](https://www.telerik.com/forums/reporting)


### More Resources

Finally, here are the general landing pages for support. It contains the information I’ve already listed, but I wanted you to also be able to find other great resources. If you experience a roadblock or dead-end, those resources are at your disposal. There you’ll find links to online video training, private Support Tickets, full sample apps and more. 

* [Support Resources for Telerik UI for Blazor](https://www.telerik.com/support/blazor-ui)
* [Support Resources for Telerik UI for ASP.NET AJAX](https://www.telerik.com/support/aspnet-ajax)
* [Support Resources for Telerik Reporting](https://www.telerik.com/support/reporting)


## Direct Assistance

Don't be afraid to ask for assistance with technical issues where self-help information isn't sufficient. Email Kat or Lance with your question(s) and we'll follow up. Being able to ask for help when you need it is a very important quality for an engineer.
