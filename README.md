# About

This is an Omni Automation solitary plug-in for OmniFocus that allows the user to create a series of numbered child tasks of the currently selected task.

_Please note that all scripts on my GitHub account (or shared elsewhere) are works in progress. If you encounter any issues or have any suggestions please let me know--and do please make sure you backup your database before running scripts from an amateur on the internet!_

## Known issues

Refer to ['issues'](https://github.com/ksalzke/created-numbered-children-omnifocus-plugin/issues) for known issues and planned changes/enhancements.

# Installation & Set-Up

1. Download the [latest release](https://github.com/ksalzke/created-numbered-children-omnifocus-plugin/releases/latest).
2. Unzip the downloaded file.
3. Move the `.omnifocusjs` file to your OmniFocus plug-in library folder (or open it to install).

# Actions

## Create Numbered Children

This action can be run on one or more selected tasks. 

It shows a form prompting the user for the number of child tasks to be created, and then creates that amount of numbered task.

For example, if the task `Do something` is selected and '4' is selected, the resultant tasks will look like this:

 - Do something
   - 1
   - 2
   - 3
   - 4