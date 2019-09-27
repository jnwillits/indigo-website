---
title: Projects
layout: page
---

<br>
<br>
<p>I build custom tools to automate data processing to include creation and distribution of reports. The Flashcard Project is an ongoing open source desktop application I developed and authored.</p>
<br>
<br>
<h2>Project Example: Desktop Application - The Flashcard Project</h2>
<ul>
<li><a href="https://github.com/jnwillits/The-Flashcard-Project">Code Repository</a></li>
</ul>

<p>x</p>

![Profile Image]({{ site.url }}/{{ site.picture-fp-screen_1280x640 }})

<br>
<br>
<h2>Project Example: Custom Calculator</h2>
<ul>
<li><a href="https://raw.githubusercontent.com/jnwillits/my-coding-projects/tic-tac-toe/fuel-credit.py">Code Repository</a></li>
</ul>

<p>I helped a truck rental business by providing a utility program to calculate credit due when trucks are returned with added fuel. The rental software they use calculates the amount to charge when fuel level is lower on return. However, it was necessary to manually determine credit when trucks were returned with added fuel. Truck types have varying fuel capacities, so the process was prone to error. The utility saves labor as well.</p>

<p>The user can set up multiple types of trucks by entering the vehicle name and tank capacity. The amount to credit per gallon must also be entered for setup. The data is automatically stored so day-to-day use of the program only requires selection of the truck type with a drop-down box and outgoing/incoming fuel levels with sliders that represent the fuel gauge.</p>

![Profile Image]({{ site.url }}/{{ site.picture-fuel-credit }})



<br>
<br>
<h2>Project Example: Excel File Processing</h2>
<ul>
<li><a href="https://raw.githubusercontent.com/jnwillits/past-due-accounts-utility/master/auction-planner-utility.py">Code Repository</a></li>
</ul>

<p>I am associated with a business that makes daily updates to an Excel spreadsheet to track a process that involves a series of dated events. The updates start by entering information from an Excel formatted report of past due balances that is exported from operational software. Obsolete data needs to be deleted from their custom spreadsheet, dates needs to be compared and updated, and new accounts are added.</p>

<p>I designed a labor-saving desktop utility that automates all of this. It automatically reads data from cells in the operational spreadsheet and makes date comparisons. It then updates and saves a new version of the custom spreadsheet. A date and time stamped backup of their file is also saved before the revisions are recorded.</p>


<br>
<br>
<h2>Project Example: Reporting Process Automation</h2>
<ul>
<li><a href="https://raw.githubusercontent.com/jnwillits/reporting-process-automation-utility/master/reporting-utility.py">Code Repository</a></li>
</ul>

<p>This is an example program that demonstrates how data can be automatically collected from multiple spreadsheets. The
program processes the data and generates report files in Excel and PDF formats.  Here is one of the input data files:</p>

![Profile Image]({{ site.url }}/{{ site.picture-automated_report_input }})

<p>Suppose you ran a new company without established operational software. At the end of each day, your sales offices
uploaded sales data in spreadsheets to your server. Then someone cut and pasted the data to another spreadsheet, using it to 
calculate sales agent productivity, sort, then paste the results to a reporting template. To save labor, reduct errors, and
improve process consistency this can be easily automated with a simple executable utility. The example code includes a GUI
interface so it does not have to run from the command line and the data file paths can be easily entered and stored.</p>

![Profile Image]({{ site.url }}/{{ site.picture-automated_report_gui }})

<p>The utility creates reports as shown below and files them in both Excel and PDF formats with file names that include date
and time information. The program could be extended to allow it to run at a specified time and automatically email the files.
Any type of output is possible, including graphs that render the data and information.</p>

![Profile Image]({{ site.url }}/{{ site.picture-automated_report_1 }})


<br>
<br>
<h2>Project Example: Report Email Utility</h2>
<ul>
<li><a href="https://raw.githubusercontent.com/jnwillits/Report-Email-Utility/master/report-email-utility.py">Code Repository</a></li>
</ul>

<p>If you are sending reports on a daily basis to an email distribution, you spend time attaching the files, writing an email subject, and identifying the distribution. This code can be compiled to an executable file and set to trigger automatically by the Windows Task Scheduler. All you have to do is make sure the files are at the specified location before the program is set to launch. There is no need to open Outlook. It prepares the email and deletes the files when it is finished. If there are no files to send, it does nothing.</p>

<br>
<br>
<h2>Project Example: Morning Emailer</h2>
<ul>
<li><a href="https://raw.githubusercontent.com/jnwillits/morning-emailer/master/morning-emailer.py">Code Repository</a></li>
</ul>

<p>Automate repetitive emails! I wrote this utility to help a business automate setting up and sending a report email – one that is done repetitively. It is useful when a range of Excel data needs to be pasted into the body of the email. The setup only needs to happen once with a simple single page GUI input form. Files are identified along with sheet and range information for the spreadsheet. Text for the subject of the email can be specified and the email distribution is also entered. Once the setup data is entered, it is stored so the email can be produced and sent with a single click.</p>

![Profile Image]({{ site.url }}/{{ site.picture-morning_emailer }})
