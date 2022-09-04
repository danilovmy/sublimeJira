# sublimeJira
Update for sublime-jira pluin with more possibilities

this is fork from https://github.com/mix86/SublimeJira.

SublimeJira
SublimeJira lets you work with Jira tickets from the comfort of your favorite editor.

Features
Create, view and update issues using Sublime Text only.
Tested integraton with online Atlassin-Jira Software

Install mix86/SublimeJira.
Replace code from this repo manually:

Usage
The plugin adds commands and some shortcuts:

- Get last 50 issues - ctrl+shift+alt+j
- Get issue – ctrl+alt+j prompt issue key and show it in a new tab
- Create issue –  ctrl+shift+alt+u create empty form for new issue in new tab
- Save issue – ctrl+alt+u save changes

Configure
Go to "Preferences => Package Settings => Sublime Jira => Settings – User" and paste some like this:

{
  "jira_server": "https://yourdomain.atlassian.net",
  "jira_login": "username",
  "jira_password": "your api key for this usecase",
  "jira_default_project": "YOURPROJECT"
}

Get statuses and usenames from jira. Allow write not whole username
Create issue form:

Project: WPSHOP
Summary: 'issue name'
Type: Task
Status: Zu erledigen
Priority: Medium
Reporter: my_email@mydomain.com
Assignee: first_letters_from_user_or_me_if_it_empty
Description: 
my description in any form
