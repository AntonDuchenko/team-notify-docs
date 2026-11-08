---
title: Privacy policy — Team Notify for Jira
---

[← Team Notify for Jira](./)

# Privacy policy

Last updated: 8 November 2026

Team Notify for Jira ("the app") is made by Anton Duchenko ("we"), contact: anton.duchenko2@gmail.com.

The app runs entirely on Atlassian Forge ("Runs on Atlassian"). It has no servers of its own and sends no data
outside Atlassian's infrastructure.

## What the app processes
To do its job, the app reads from your Atlassian site, at the moment it is needed:
- the Team field of a work item when it is created or changed, and the work item's key and project;
- the Atlassian account IDs of the members of that team, to address Jira's notification email;
- for "My teams' work": the account ID of the person viewing the page, the names of their teams, and the key, summary
  and status of the matching work items.

These are processed in memory and are not stored by the app.

## What the app stores
One settings record per site, in Atlassian's Forge storage: whether the app is on, the IDs of the selected projects,
and whether the person who made a change is notified. It contains no personal data.

## Logs
Each sent notification writes one log line with the number of recipients, the team name and the work item key. No
account IDs, names or email addresses are logged. Logs are kept by Atlassian and are visible to us in the Atlassian
developer console, for troubleshooting only.

## Emails
Notification emails are sent by Jira through its own notification service. We never see or store email addresses.

## Sharing
We do not sell or share any data. The only processor is Atlassian, under its own terms and privacy policy.

## Data residency and security
Data stays in Atlassian's Forge platform and follows your site's data residency. Encryption, backups and access
control are provided by Atlassian.

## Deletion
Uninstalling the app deletes its stored settings. To ask about data, write to anton.duchenko2@gmail.com.

## Changes
We will update this page if the app starts processing different data, and change the date above.
