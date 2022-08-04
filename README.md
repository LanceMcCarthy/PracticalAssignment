# Practical Assignment

Your mission, if you choose to accept, is to build the *running application equivalent of your resume*. This message will self-destruct in 3… 2… 1…

![self-destruct-mission-impossible](https://user-images.githubusercontent.com/3520532/167459946-9441a9c6-bcc4-4243-893d-334097d2d1ca.gif)

### Instructions

1. Download this starter template
    - Option 1 - If you're familair with GitHub, you can clone/fork this repo and work in there.
    - Option 2 - Download the ZIP (1. Expand the green "Code" button at the top. 2. Select "Download ZIP")
2. Complete your assignment (directions below). Note: do your work in the `src/` folder.
3. Submit the assignment
    - Option 1 (GitHub). Commit the code to your fork's main branch and email the URL to your repo to Kat.
    - Option 2 (ZIP). You can zip up everything and email it to Kat (important, so that you don't have a billion GB ZIP file size, delete all the **bin** and **obj** folders before zipping it up)

> If your project needs special instructions for setup and/or use, please include those directions with your submission.

#### Project Structure

Depending on how many parts your submission has, you might be wondering how to organize it. Here's some general guidance:

- If your submission only has one solution (`.sln`) file regardless of how many projects it contains, put the sln in the `/src` folder.
    - *real world example: see my [Cat Flusher](https://github.com/LanceMcCarthy/Flusher) repo's `/src` folder*.
- If your submission has multiple technologies that don't work well inside the same folder, then use a sub-folder for each thing.
    - *real-world example: see my [DevOpsExamples](https://github.com/LanceMcCarthy/DevOpsExamples) repo's `/src` folder.*

## Assignment Guidelines

Here are the general guidelines for the assignment:

* You have complete freedom over the project’s vision and direction; this is intended for you to be able to use the platform features to show of your skills. Be creative, show your style and interest, and most importantly.. *have fun*.

* Part 1. The Main App: Choose your preferred option to build the main application 🚀
    * Use **Telerik UI for Blazor** (uses modern ASP.NET Core Blazor and .NET 6)
    * Use **Telerik UI for ASP.NET AJAX** aka Webforms (uses older-style .NET Framework)
* Part 2. Add **Telerik Reporting** to the project by creating a Report and using the HTML5 ReportViewer to display that report in the main app. This will demonstrate:
    * Your ability to use a SQL data source to render information in the Report
    * You ability to use a REST API, the Reporting REST API is already built, you only need to add it (details in documentation links below).

> Bonus points for being creative and thinking outside the box with product features. Think about different ways you can can use both the main application, as well as the Report, to... how does apple say it?..."reimagine" your resumé 🤓

> Don't be frightented by the way the task initially sounds. A few of the terms I use are Telerik product-specific and will be unfamiliar to you. Your fundamental .NET experience will be more than enough to carry you through the assignment, and your ability to follow documentation will take you the rest of the way.

## Resources

Here are the resources you’ll need to help implement the assignment.

### Documentation

#### Docs for Part 1 - Building the main application

* [Telerik UI for Blazor (if you chose option 1)](https://docs.telerik.com/blazor-ui/introduction) - If you chose option 1 for the main app
    * [Getting started](https://docs.telerik.com/devtools/aspnet-ajax/getting-started/first-steps-msi) (server-side Blazor)
* [Telerik UI for ASP.NET AJAX](https://docs.telerik.com/devtools/aspnet-ajax/introduction) - If you chose option 2 for the main app
    * [Getting Started](https://docs.telerik.com/devtools/aspnet-ajax/getting-started/first-steps-msi) (using MSI installer)

#### Docs for Part 2 - Adding a Telerik Reporting

* [Telerik Reporting](https://docs.telerik.com/reporting/overview)
    * [Video Onboarding](https://docs.telerik.com/reporting/getting-started/video-onboarding) course - This is only 2 hours and shows you a lot of good getting started information.
    * [Desiging Reports Guide](https://docs.telerik.com/reporting/getting-started/first-steps-designing) - This quick tutorial is to show you some basic info on creating a Report.
    * [Displaying Reports Guide](https://docs.telerik.com/reporting/getting-started/first-steps-integrating) - This quick tutorial is to create a quick throw-away webapp project to familiarize you with how a Report Viewer is used.
    * [How to display Reports in an application](https://docs.telerik.com/reporting/using-reports-in-applications/overview) - These docs are for the real deal. After yo've designed your report, now it's time to add a Report Viewer to your app-of-choice and display it at runtime.
        * [In a Blazor project](https://docs.telerik.com/reporting/using-reports-in-applications/display-reports-in-applications/web-application/blazor-report-viewer/overview)
        * [In an AJAX project](https://docs.telerik.com/reporting/using-reports-in-applications/display-reports-in-applications/web-application/html5-asp.net-web-forms-report-viewer/overview)

### Important Note

In order to get the things oyu need to build this stuff/watch training, you will need a license for the products you chose to use. You can automatically get a trial license for any of the items above by clicking "DOWNLOAD FREE TRIAL" button on any product's Overview page. 

- [Go here for Telerik Reporting](https://www.telerik.com/products/reporting.aspx), 
- [Go here for UI for Blazor](https://www.telerik.com/blazor-ui)
- [Go here for UI for ASP.NET AJAX](https://www.telerik.com/products/aspnet-ajax.aspx).

Downloading the trial installer will automatically assign a new trial license to your Telerik account, and you're good to go from there. Don't hesitate to ask for assistance form Lance if you get stuck on this.


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

Don't be afraid to ask for assistance with technical issues where self-help information isn't sufficient. Email Kat or Lance with your question(s) and we'll follow up. Being able to ask for help when you need it is a *very important* quality for an engineer.
