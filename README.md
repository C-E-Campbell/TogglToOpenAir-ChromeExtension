# TogglToOpenAir-ChromeExtension
This is a Google Chrome Extension that provides a way to create a timesheet in OpenAir based on tracking data in Toggl

#### Pre-requisites:
This requires the following to be useful:
- [Toggl](https://toggl.com/) for tracking your time
- [OpenAir](https://www.openair.com/index.pl) for submitting a timesheet

#### To use:

###### Tracking time with Toggl:
1) Download [Toggl](https://toggl.com/)
2) Create or import Clients and Projects--synonymous with Projects and Tasks in OpenAir
   - If purchased, use the billable feature in Toggl to mark projects as billable; otherwise, adding "Billable" to Projects, e.g. Billable Task, billable task, My Project - billable, My Project [Billable], or a time entry's Tags treat that time as billable
   - Import Clients and Projects using an existing timesheet in OpenAir and the TogglToOpenAir instructions
3) Start using Toggl to track time

###### Creating an OpenAir timesheet with Toggl data:
1) Go to [OpenAir](https://www.openair.com/index.pl)
2) Create a brand new timesheet
3) Click the TogglToOpenAir icon in the toolbar
4) Go to Toggl to get the Toggl API key--this can be found at the bottom of the [Toggl Profile](https://toggl.com/app/profile)
   - Copy and paste the API key into the appropriate textbox in the Chrome Extension
5) Specify the start date--by default it is the first date without time entries in a timesheet
6) Specify if time entries should be rounded to the nearest quarter hour, i.e. 15 minutes--by default, rounding is off
7) Specify if time entries should be grouped by task or description--by default, group by description
8) Click the *Create* button
9) Review any errors and verify the results